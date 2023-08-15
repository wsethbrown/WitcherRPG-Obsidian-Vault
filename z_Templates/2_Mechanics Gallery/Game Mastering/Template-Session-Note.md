<%*
const counter = tp.file.find_tfile('Session-counter.txt') // find the txt with counter. file need to be in the same folder as the template and it needs to contain only a single integer.

const prevsession = tp.file.find_tfile('previous-session-name.txt')
let psession = await app.vault.read(prevsession)

let count = parseInt(await app.vault.read(counter)) // read the file
count++ // increment the count
await app.vault.modify(counter, `${count}`) //save the updated value

//initialize variables
const path = "10 Session Notes" // path notes are in

let date = await tp.system.prompt("Date (YYYY-MM-DD)")
//let date = tp.date.now("YYYY-MM-DD")
//let fileNo = 1 // Number to be incremented
let baseFileName = date + " Session " // Base file name
let sFileNo = String(count).padStart(3, '0') // Convert file number to string and add padding
let fileName = path + "/" + baseFileName + sFileNo + ".md"// Base file name plus padded file number
let exists = await tp.file.exists(fileName) // Check to see if file already exists

// Final file name using incremented file number
let finName = baseFileName + sFileNo
await app.vault.modify(prevsession, `${finName}`)
await tp.file.move(path + "/" + finName)
_%>
---
NoteIcon: Session
SessionNum: <% count.toString().padStart(3, '0')  %>
type: Session
fc-calendar: Darvollian
fc-category: Adventure
Chars: 
fc-date:
    year: 1388
    month: White
    day: 8
creation-date: <% tp.date.now("YYYY-MM-DD") %>
Summary:
tag: Session, tbp
---


# <% finName %>



## Session Summary
>[!note] <% finName %>
> textddd
> ^Summary

## Recap previous Session 
![[<% psession %>#^Summary]]
^Recap


## Log

<% tp.file.cursor(1) %>
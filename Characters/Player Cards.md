
> [!cards|dataview 4]
>```dataview
TABLE WITHOUT ID
>	link(file.path, name) AS "Name",
>	embed(token) AS "Art",
>	race AS "Race",
>	class AS "Class",
>	specialty AS "Subclass",
>	background AS "Background"
>FROM "Characters"
>WHERE contains(chars, "story")
>SORT file.name asc
>```
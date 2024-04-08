```dataview
>> TABLE WITHOUT ID
>> "<span style='display: block; text-align: center; margin-bottom: 5px;'>" + link(file.link, Title) + "</span>" AS Title,
>> embed(link(art)) AS "Art"
> FROM !"z_Templates"
>> WHERE contains(tags, "Party")
>> SORT file.name asc
>> ```
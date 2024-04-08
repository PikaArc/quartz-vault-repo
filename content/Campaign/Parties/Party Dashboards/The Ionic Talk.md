```dataview
>> TABLE WITHOUT ID
>>	embed(link(art)) AS "Art",
>>     "<span style='display: block; text-align: center; margin-bottom: 5px;'>" + link(file.link, Title) + "</span>" AS Title
>> FROM "Campaign"
>> WHERE econtains(whichparty, this.file.link) AND contains(tags, "Character") AND !contains(condition, "Dead")
>> SORT tags DESC, file.name ASC
>>```
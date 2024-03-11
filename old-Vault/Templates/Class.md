<%*
let title = tp.file.title
let course = "Unknown"
let chapiter = 0

if (title.startsWith("Untitled")) { 
	title = await tp.system.prompt("Title"); 
	await tp.file.rename(title); 
} 

session = await tp.system.prompt("Session : (INS-SSS-YYYY)");
courseId = await tp.system.prompt("Course Tag"); 
teacherName = await tp.system.prompt("Nom professeur");

tR += "---"
%>
type: Class
title: <%* tR += title %>
session: <%session%>
id : <%courseId%>
teacher: <%teacherName%>
created: <%tp.file.creation_date()%>
---
# <%* tR += title %> 
----


#### Professeur
----
[[<%teacherName%>]]

#### Objectifs
------

#### Evaluations:
----

| Done ? | Travail | Due date | Note |
|--------|---------|----------|------|

#### Aide
----

#### Cours:
----
```dataview
table chapiter as "Chapiter", created as "Creation date"
where type = "Knowledge" and class = ""
sort chapiter asc
```
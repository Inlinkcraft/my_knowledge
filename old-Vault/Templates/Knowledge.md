<%*
let title = tp.file.title
let course = "Unknown"
let courseId = "Unknown"
let chapiter = "Chapitre"

if (title.startsWith("Untitled")) { 
	title = await tp.system.prompt("Title"); 
	await tp.file.rename(title); 
} 

course = await tp.system.prompt("Course"); 
courseId = await tp.system.prompt("Course ID"); 
chapiter = await tp.system.prompt("Chapiter Number");

tR += "---"
%>
type: Knowledge
class: <%course%>
id: <%courseId%>
chapiter: Chapitre-<%chapiter%>
title: <%* tR += title %> 
tags: Knowledge/<%courseId%>/Chapitre-<%chapiter%>/<%* tR += title.replaceAll(" ", "_").replaceAll("'","") %> 
created: <%tp.file.creation_date()%>
---
# <%* tR += title %> 
----
résumé

## Related Subjects
----
#### Links
----
- 
#### flashcard 
----
- 
<%*
let name = tp.file.title

if (name.startsWith("Untitled")) { 
	name = await tp.system.prompt("Title"); 
	await tp.file.rename(name + " overview"); 
} 

let description = await tp.system.prompt("A little project desription"); 

tR += "---"
%>
type : project
name : <%name%>
estimated_price : 0
amas_funds : 0
expense : 0
current_budget : 0
---
# <%name + " overview"%>
----
<%description%>

## Status
----
Kanban : [[<%name + " status"%>]]


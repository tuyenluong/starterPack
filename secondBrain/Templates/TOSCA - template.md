---
Creation_date: <% tp.file.creation_date() %>
Modification_date: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Indexes:
---
<% tp.file.rename("TOSCA - ") %>

----


```dataview
table file.name as Title, Creation_date, Modification_date
from [[]]  sort Creation_date DESC
```

























---
## Flash cards section


``` dataview
table "<small>"+file.folder+"</small>" as "📁" where 
	file.ctime >= date("<% tp.file.creation_date("YYYY-MM-DD") %>") or
	file.mtime >= date("<% tp.file.creation_date("YYYY-MM-DD") %>") sort file.folder
```


| Name       | Type           | Notes  |
| :------------- | :-------------| :----- |
| Id      | uniqueidentifier | Primary key |
| ForeignKeyId      | uniqueidentifier      |   Key of vendor associated record |
| Note      | varchar(max) | A blob of text describing the associated record etc. |
| Link      | varchar(255) | A link to an associated piece of information (http, ftp, mailto, local etc.) |
| AuthorName      | varchar(150) | The author name |
| AuthorEmail      | varchar(150) | the author email |
| Modified      | DateTime | The date of the last time this record was modified |

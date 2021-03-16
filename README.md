# License Templates

These files are designed to be used by `velocity`, template for copyright profiles in Intellij

## Format/Structure

The template uses variables as placeholders to substitute values specified by
`velocity`.

## Templates for coppyright to be used in Intellij copyright profiles

* $today.year : the year of the software's copyright.
* `{{ organization }}`: the name of the organization or individual who holds
the copyright to the software.
* $project.name : the name of the software project.

### Available variables 

| Name | Type| Comment |
| :---         |   :---        |       :---    |
|$today	|DateInfo |	The current date and time.|
|$file.fileName	|String	|The name of the currently opened file where the notice is to be generated.|
|$file.pathName	|String	|The complete path and name of the currently opened file where the notice is to be generated.|
 |$file.className	 |String |	The name of the currently opened Java file where the notice is to be generated. |
 |$file.qualifiedClassName	 |String |	The fully qualified name of the currently opened file where the notice is to be generated. |
 |$file.lastModified	 |DateInfo	 |The date and time when the current file was last changed. |
 |$project.name |	String	 |The name of the current project. |
 |$module.name	 |String	 |The name of the current module. |
 |$username	 |String	 |The name of the current user. |

 
 
 #### DateInfo has the following properties: 
 | &nbsp; | &nbsp;|  &nbsp; |
| :---         |   :---        |       :---    |
 |year	 |int	 |The current year. |
 |month	 |int	 |The current month (1-12). |
 |day	 |int	 |The current date of month (1-31). |
 |hour	 |int	 |The current hour (0-11). |
 |hour24	 |int	|The current hour (0-23). |
 |minute	 |int |	The current minute of the hour (0-59). |
 |second |	int |	The current second of the minute (0-59). |
 
 #### DateInfo has the following method:
  | &nbsp; | &nbsp;|  &nbsp; |
| :---         |   :---        |       :---    |
 |format(String format)|String	|Date and time formats that are specified by date and time pattern strings. See java.text.SimpleDateFormat format options. |



## Copyright

All licenses in this repository are copyrighted by their respective authors.
Everything else is released under CC0. See `LICENSE` for details.

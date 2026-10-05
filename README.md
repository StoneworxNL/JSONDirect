# JSONDirect
This module allows you to directly interact with JSON data, without import/export mappings. This allows you to generate complex data structures directly from data and read specific information without generating a non-persistent structure in Mendix.

This is accomplished through a variety of Java actions that set up a context and then allow you to interact directly with the loaded JSON.

Paths can be specified in JSON, XPath and Folder styles.

## Included Java actions
| Category | Action | Description |
|--|--|--|
| Read | Parse| Parses a new JSON into context |
| | GetAllPaths | Returns every unique path found in the structure |
| | GetByPath | Returns the JSON node at the specified path |
| | GetFieldsByPath| Returns all fields and their values at the specified path |
|  | GetValueByPath | Returns the value at the specified path |
| Write | Start | Creates a new JSON context |
| | Return | Return JSON string |
| | AddByPath | Writes a value to the path specified with the specified value type |

## Examples
The module includes a test page the JSON parsing/reading features.

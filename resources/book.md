# Book type

The book resource represents the properties of a book within the system.

### Tasks on Book

The following tasks are available for Book resources.

| Task   | Return Type | Example |
|:-------|:------------|:------------|


### JSON representation

Here is a JSON representation of Book.

<!-- { "blockType": "resource",
"@type": "book",
"optionalProperties": [] } -->
```json
{
  "id": "string",
  "title": "string",
  "description": "string",
  "authors": [ {"@type": "author"} ],
  "purchaseUrl": "url",
  "lastModifiedDateTime": "datetime",
  "costs": {"@type": "costStructure" }
}
```

### Properties

| Property | Type | Description |
|:---------|:-----|:------------|
| **id**   | String | Unique identifier for the book. |
| **title** | String | The title of the book. |
| **description** | String | Descriptive text for the book, including an abstract. |
| **authors** | Collection([Author](author.md)) | A collection of author resources that represent the authors of the book. |
| **purchaseUrl** | String - URL | A fully qualified URL to the purchase page for this book. |
| **lastModifiedDatetime** | DateTime | The date and time the book record was last modified. |
| **costs** | [Costs](costs.md) | A collection of properties that define the cost structure for the book. |

<!-- {
"type": "#page.annotation",
"description": "",
"keywords": "",
"section": "",
"tocPath": "",
"tocBookmarks": {}
} -->

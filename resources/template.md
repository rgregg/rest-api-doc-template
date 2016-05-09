# {{Resource.Name}} type

{{Resource.Description}}

### Tasks on {{Resource.Name}}

The following tasks are available for {{Resource.Name}} resources.

| Task   | Return Type | Example |
|:-------|:------------|:------------|
{{#foreach Resource.Tasks}}
| {{Name}} | {{ReturnType}} | {{Example}}
{{/foreach}}


### JSON representation

Here is a JSON representation of `{{Resource.Name}}`.

<!-- { "blockType": "resource",
"@type": "{{Resource.Name}}",
"optionalProperties": [] } -->
```
{{Resource.JsonExample}}
```

### Properties

| Property | Type | Description |
|:---------|:-----|:------------|
{{#foreach Resource.Properties}}
| {{Name}} | {{ReturnType}} | {{Description}}
{{/foreach}}

### Relationships

| Property | Type | Description |
|:---------|:-----|:------------|
{{#foreach Resource.Properties}}
| {{Name}} | {{ReturnType}} | {{Description}}
{{/foreach}}

{{if Resource.Remarks }}
### Remarks

{{Resource.Remarks}}
{{/if}}

<!-- {
"type": "#page.annotation",
"description": "{{Page.Description}}",
"keywords": "{{Page.Keywords}}",
"section": "{{Page.Section}}",
"tocPath": "{{Page.TocPath}}",
"tocBookmarks": {}
} -->

# Registry Deleted

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Registry Deleted",
    "registry": {
        "registryType": "<registryType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|registryType|string|The type of gift registry|Wedding, Baby, Birth Day, Anniversary|||||||

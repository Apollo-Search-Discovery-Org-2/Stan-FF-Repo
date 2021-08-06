# Report Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Report Listing Item Clicked",
    "listingDisplayed": {
        "sortOrder": "<sortOrder>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|sortOrder|string|Indicates the sort order.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||

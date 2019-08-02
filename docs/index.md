# Доментация Fresh-Byte Platform

## API
### Scheme API

URL | Метод | Описание
------------ | ------------- | -------------
/api/scheme/applications | GET |
/api/scheme/applications/:appid | GET |
/api/scheme/applications/:appid/icon/:fileName | GET |
/api/scheme/applications/:appid/views | GET |
/api/scheme/applications/:appid/views/:viewid | GET |
/api/scheme/applications/:appid/views/:viewId/actions | GET |
/api/scheme/applications/:appid/views/:viewId/actions/:actionid | GET |
/api/scheme/applications/:appid/views/:viewid/entries | GET |
/api/scheme/applications/:appid/views/:viewid/entries/:entryId | GET |
/api/scheme/applications/:appid/forms | GET |
/api/scheme/applications/:appid/forms/:formid | GET |
/api/scheme/applications/:appid/forms/:formid/actions | GET |
/api/scheme/applications/:appid/forms/:formid/actions/:actionid | GET |
/api/scheme/applications/:appid/forms/:formid/fields | GET |
/api/scheme/applications/:appid/forms/:formid/fields/:fieldid | GET |
/api/scheme/applications/:appid/forms/:formid/embeddedviews | GET |
/api/applications/:appId/forms/:formId/embeddedviews/:embeddedViewId | GET |


### Data API

URL | Метод | Описание
------------ | ------------- | -------------
/api/data/*ENTITY_URI* | GET |
/api/data/*ENTITY_URI* | POST |
/api/data/*ENTITY_URI* | PUT |
/api/data/*ENTITY_URI* | DELETE |


### Release 1.5
Features added:
* Ignore serialization and deserialization with @JsonIgnore decorator - thanks [@devpreview](https://github.com/devpreview).
* Removed ```reflect-metadata``` from  required dependencies list - thanks [@devpreview](https://github.com/devpreview).
* Serialize / deserialize array keeping the order - thanks [@vapkse](https://github.com/vapkse)

Defect fixes:
* [Enable String Serializer to support strings with special characters](https://github.com/shakilsiraj/json-object-mapper/pull/6). Thanks [@ironchimp](https://github.com/ironchimp)
* [deserializeArray returns undefined when called on an empty array](https://github.com/shakilsiraj/json-object-mapper/pull/19). Thanks [@devpreview](https://github.com/devpreview) 
* [nested array is undefined](https://github.com/shakilsiraj/json-object-mapper/pull/21). Thanks [@devpreview](https://github.com/devpreview) 
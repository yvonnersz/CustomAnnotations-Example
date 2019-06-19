## Create a simple custom annotation

#### Adapted from Baeldung "[Creating a Custom Annotation in Java](https://www.baeldung.com/java-custom-annotation)"

1. Create 3 custom annotations
   * `@JsonSerializable` - Indicates that class is serializable to json
   * `@JsonElement` - Indicates that the field is to be serialized
   * `@Init` - Identifies the method that will initialize the data before serialization
1. Create a `Person` class and add our new annotations
1. Create a `ObjectToJsonConverter` class to serialize the object to json
1. Create a test to exercise your code

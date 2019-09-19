# Avro Tools

## Avro Commands

- Avro to Json
  * `java -jar avro-tools-1.8.2.jar tojson -pretty example.avro > example.json`
- Json to Avro
  * `java -jar avro-tools-1.8.2.jar fromjson --schema-file example.avsc example.json > example.avro`
- Generate Avro Schema
  * `java -jar avro-tools-1.8.2.jar getschema example.avro > example.avsc`

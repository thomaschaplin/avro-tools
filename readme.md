# Algomi QA Avro

## Documentation / Guide

Please read the below guide for a full explanation of how to use this repository

https://confluence.algomi.net/display/PJ/Algomi+ALFA+Usage+Analytics

## Avro Commands

- Avro to Json
  * `java -jar avro-tools-1.8.2.jar tojson -pretty example.avro > example.json`
- Json to Avro
  * `java -jar avro-tools-1.8.2.jar fromjson --schema-file example.avsc example.json > example.avro`
- Generate Avro Schema
  * `java -jar avro-tools-1.8.2.jar getschema example.avro > example.avsc`

# Getting Started

## Minimum Reproducible Test Case for an OpenAPI Bug

This reproduces a bug during code generation. Run the following command:

`mvn openapi-generator:generate`

It should generate the code specified by the .yaml file. Instead, it gives the following error message:

`Failed to execute goal org.openapitools:openapi-generator-maven-plugin:5.0.0-SNAPSHOT:generate (default-cli) on project bug: The parameters 'inputSpec' for goal org.openapitools:openapi-generator-maven-plugin:5.0.0-SNAPSHOT:generate are missing or invalid`

The trouble with this message is that inputSpec is defined correctly. It points to a properly formatted .yaml file that uses the OpenAPI 3.0.0 spec.


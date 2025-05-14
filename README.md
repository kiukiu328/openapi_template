# openapi_template
A collection of OpenAPI Generator templates tailored to meet the needs of a PostgREST API.

Major features:
1. Allow models to be nullable for patch requests.
2. Allow users to add RawQuery parameters for complex queries.
 
OpenAPI Generator Templates  
`openapi-generator author template -g <generator> -o <outputDir> [--library <library>]`  

Command to generate a template for a specific generator:  
`openapi-generator author template -g typescript-fetch -o typescript-fetch`   
`openapi-generator author template -g go-gin-server -o go-gin-server`  
`openapi-generator author template -g csharp -o csharp-unityWebRequest --library unityWebRequest`
## Installation

To download only a specific template without cloning the entire repository, use the links below:

* [Download Go Gin Server Template](https://downgit.github.io/#/home?url=https://github.com/kiukiu328/openapi_template/tree/main/go-gin-server)
* [Download Typescript Fetch Client Template](https://downgit.github.io/#/home?url=https://github.com/kiukiu328/openapi_template/tree/main/typescript-fetch-client)
* [Download Dart Client Template](https://downgit.github.io/#/home?url=https://github.com/kiukiu328/openapi_template/tree/main/dart-client)
* [Download C# UnityWebRequest Client Template](https://downgit.github.io/#/home?url=https://github.com/kiukiu328/openapi_template/tree/main/csharp-unityWebRequest-client)


# openapi_template
A collection of OpenAPI Generator templates tailored to meet the needs of a PostgREST API.

Major features:
1. Allow models to be nullable for patch requests.
2. Allow users to add RawQuery parameters for complex queries.
 
OpenAPI Generator Templates  
`openapi-generator author template -g <generator> -o <outputDir> [--library <library>]`  

Command to generate a template for a specific generator:  
`openapi-generator author template -g dart -o dart`  
`openapi-generator author template -g typescript-fetch -o typescript-fetch`   
`openapi-generator author template -g go-gin-server -o go-gin-server`  
`openapi-generator author template -g csharp -o csharp-unityWebRequest --library unityWebRequest`



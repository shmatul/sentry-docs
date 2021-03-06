---
# This file is automatically generated from the API using `api-docs/generate.py`
# Do not manually this file.
{
  "api_path": "/api/0/organizations/{organization_slug}/releases/{version}/", 
  "authentication": "required", 
  "description": "Return details on an individual release.", 
  "example_request": "GET /api/0/organizations/the-interstellar-jurisdiction/releases/17642328ead24b51867165985996d04b29310337/ HTTP/1.1\nHost: sentry.io\nAuthorization: Bearer <token>", 
  "example_response": "HTTP/1.1 200 OK\nContent-Length: 454\nX-XSS-Protection: 1; mode=block\nContent-Language: en\nX-Content-Type-Options: nosniff\nVary: Accept-Language, Cookie\nAllow: GET, PUT, DELETE, HEAD, OPTIONS\nX-Frame-Options: deny\nContent-Type: application/json\n\n{\n  \"authors\": [], \n  \"commitCount\": 0, \n  \"data\": {}, \n  \"dateCreated\": \"2018-11-06T21:19:55.146Z\", \n  \"dateReleased\": null, \n  \"deployCount\": 0, \n  \"firstEvent\": \"2018-11-06T21:19:55.271Z\", \n  \"lastCommit\": null, \n  \"lastDeploy\": null, \n  \"lastEvent\": \"2018-11-06T21:19:55.271Z\", \n  \"newGroups\": 0, \n  \"owner\": null, \n  \"projects\": [\n    {\n      \"name\": \"Pump Station\", \n      \"slug\": \"pump-station\"\n    }\n  ], \n  \"ref\": null, \n  \"shortVersion\": \"1764232\", \n  \"url\": null, \n  \"version\": \"17642328ead24b51867165985996d04b29310337\"\n}", 
  "method": "GET", 
  "parameters": null, 
  "path_parameters": [
    {
      "description": "the slug of the organization the release belongs to.", 
      "name": "organization_slug", 
      "type": "string"
    }, 
    {
      "description": "the version identifier of the release.", 
      "name": "version", 
      "type": "string"
    }
  ], 
  "query_parameters": null, 
  "sidebar_order": 3, 
  "title": "Retrieve an Organization's Release", 
  "warning": null
}
---

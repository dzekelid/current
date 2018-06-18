{
  "info": {
    "name": "Pivotal Tracker Get Projects Project Iterations Current",
    "_postman_id": "39206614-9649-4ab1-88b3-c8c2d11434a9",
    "description": "Retrieves iterations from the \"current\" group, with stories.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Projects",
      "item": [
        {
          "id": "2590aaba-687e-44de-8ef6-fc001548462f",
          "name": "getProjectsProjectIterationsCurrent",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/iterations/current"
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves iterations from the \"current\" group, with stories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1749528c-0753-4c16-a4e4-dcf8e6d5fdad"
            }
          ]
        }
      ]
    }
  ]
}
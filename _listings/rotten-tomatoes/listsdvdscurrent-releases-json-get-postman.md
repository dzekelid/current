{
  "info": {
    "name": "Rotten Tomatoes Get Lists Dvds Current Releases",
    "_postman_id": "6269a426-9697-4035-9ed7-60d589ec3c32",
    "description": "Get lists dvds current releases.json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "7f1bb977-706d-4577-9023-fa724cc050d8",
          "name": "getListsDvdsCurrentReleases.json",
          "request": {
            "url": "http://api.rottentomatoes.com/api/public/v1.0/lists/dvds/current_releases.json?country=%7B%7D&page=%7B%7D&page_limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get lists dvds current releases.json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01d5ab51-18a9-4370-a791-1bbc257383eb"
            }
          ]
        }
      ]
    }
  ]
}
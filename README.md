# Rest-API![Screenshot 2025-05-01 200601](https://github.com/user-attachments/assets/120ae97f-2785-4352-9b51-50cf997eaf54)
![Screenshot 2025-05-01 200948](https://github.com/user-attachments/assets/e89c8666-b5af-4e47-89f9-a61492c5c68d)
![Screenshot 2025-05-01 201110](https://github.com/user-attachments/assets/489bb9fa-2d4d-4032-b6c7-bb8a3eba89d7)
![Screenshot 2025-05-01 201150](https://github.com/user-attachments/assets/f8706a49-762c-49c3-a60e-8662196ad5eb)
![Screenshot 2025-05-01 201202](https://github.com/user-attachments/assets/1c2325dd-a425-472d-9be7-6fc4bfd4d90d)
![Screenshot 2025-05-01 201206](https://github.com/user-attachments/assets/7d51f779-cb8e-49b9-afc8-b57be0a1b2c6)
![Screenshot 2025-05-01 201402](https://github.com/user-attachments/assets/157a55d4-0028-4f28-b70b-506e98797caf)
![Screenshot 2025-05-01 201437](https://github.com/user-attachments/assets/f9962c2b-36fb-4cee-adba-f69057e2daba)
![Screenshot 2025-05-01 195615](https://github.com/user-attachments/assets/279e89fe-26ef-4f84-b2a4-1ef33220ebb9)
![Screenshot 2025-05-01 200551](https://github.com/user-attachments/assets/c22060e5-3b7c-4b00-b2af-ed33022c85ca)
[Latian Api.postman_collection.json](https://github.com/user-attachments/files/20000149/Latian.Api.postman_collection.json){
	"info": {
		"_postman_id": "bd0e3052-2e06-429b-9019-689b7d68020a",
		"name": "Latian Api",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "44594604",
		"_collection_link": "https://dennishansensutanto.postman.co/workspace/Dennis-Hansen-Sutanto's-Workspa~5947daba-d006-4107-83e9-f5ebc195654b/collection/44594604-bd0e3052-2e06-429b-9019-689b7d68020a?action=share&source=collection_link&creator=44594604"
	},
	"item": [
		{
			"name": "get",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://localhost:4567/api/books",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "4567",
					"path": [
						"api",
						"books"
					]
				}
			},
			"response": []
		},
		{
			"name": "post",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"title\": \"Belajar Java\",\r\n  \"author\": \"Andru\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:4567/api/books",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "4567",
					"path": [
						"api",
						"books"
					]
				}
			},
			"response": []
		},
		{
			"name": "put",
			"request": {
				"method": "PUT",
				"header": []
			},
			"response": []
		},
		{
			"name": "delete",
			"request": {
				"method": "DELETE",
				"header": []
			},
			"response": []
		}
	]
}

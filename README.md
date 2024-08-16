Postman work as a third party package.
api link----
GET()       --http://127.0.0.1:8000/api/list/
POST()      --http://127.0.0.1:8000/api/list/
                tick=body-->raw-->json
                {
                    "username": "JaiPatel",
                    "first_name": "Jai",
                    "last_name": "Patel",
                    "email": "Jai@gmail.com",
                    "password": "jai@123"
                }

PUT()       --http://127.0.0.1:8000/api/list/
                tick=body-->raw-->json
                {
                    "username": "JaiPatel",
                    "first_name": "Jai",
                    "last_name": "Patel",
                    "email": "Jai@gmail.com",
                    "password": "jai@123"
                }
PATCH()     --http://127.0.0.1:8000/api/list/
                tick=body-->raw-->json
                { "username": "JaiPatel",
                    "first_name": "Jai",
                    "last_name": "Patel",
                }
DELETE()    --http://127.0.0.1:8000/api/list/
tick=body-->raw-->json
                {
                    "id": 1,
                }

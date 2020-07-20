# DRF-rest-api-starter-pack
A REST API starter pack. Make models, serializers and instantly you have a deployable and functional API with documentation ready. 


### Tech Stack
---
- Python
- Django
- Django Rest Framework
- DRF-yasg 
- Gunicorn
- Heroku
- Swagger
- Redoc


### Features
---
- REST API with CRUD functionality for all the provided models.
- Sqlite3 DB is used for backend, can be changed to Postgres.
- Browsable API endpoints for visual navigation. 
- Swagger Documentation and testing for URL endpoints. 
- Redoc autogenerated documentation.
- Deployed on Heroku.
- List view Filtering. 
- Strict REST standards. 
- Token based authentication. 
- I18n language agnostic and translation. 

### Endpoints
---

URL |  Purpose 
---| ---
/swagger| Swagger documentation
/redoc | Redoc documentation
/  | API root with browsable models and filtering
/?format=json | JSON results
/?format=api | HTML browsable view
/token | Obtain Token for Auth

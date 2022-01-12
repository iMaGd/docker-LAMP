### Quick start
- Change ENV variables to your desired one in `.docker/.env`.
- Run the following for first time to build image and containers
	- `set -a && source .docker/.env && docker-compose up -d --build `

### To run development LAMP
* To start server:
	- `docker-compose up -d`

* To stop server:
	- `docker-compose down`

### Server
- Application is available at: `http://localhost:8101/`
- PhpMyAdmin: `http://localhost:8102/`


### Database
- MySQL data persists at: `.docker/volumes/mysql`

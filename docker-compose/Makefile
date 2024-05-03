run_web:
	docker compose up web -db

run_db:
	docker compose up db -d

run_back:
	docker compose up backend -d

run_front:
	docker compose up frontend -d

run_newman:
	docker compose up backend_test -d

start_all:
	docker compose up -d

down:
	docker compose down

newman:
	newman run api-testing/collections/postmanForTest.postman_collection.json
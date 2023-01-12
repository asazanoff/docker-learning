run:
	docker run -d -p 3000:3000 --rm -v logs:/app/data --name logsapp asazanoff/logsapp:volumes

stop:
	docker stop logsapp

run-dev:
	docker run -d -p 3000:3000 --rm -v logs:/app/data -v /app/node_modules -v "D:\OneDrive\git\docker-learning\logs-app\:/app" --name logsapp asazanoff/logsapp:volumes

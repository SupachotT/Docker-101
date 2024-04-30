imageRun:
	docker image build -t domo-nginx_image:1.0 .

containerRun:
	docker container run -d --name nginx_server -p 8000:80 domo-nginx_image:1.0

pushImage:
	docker push demo-nginx_image:1.0
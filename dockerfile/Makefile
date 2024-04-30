imageRun:
	docker image build -t demo-nginx_image:1.0 .

containerRun:
	docker container run -d --name nginx_server -p 8000:80 demo-nginx_image:1.0

pushImage:
	docker push supachott/demo-nginx_image:1.0

changeTag:
	docker image tag demo-nginx_image:1.0 supachott/demo-nginx_image:1.0
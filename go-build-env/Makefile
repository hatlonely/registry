version=1.0.0
repository=go-build-env
user=hatlonely

.PHONY: build push

build:
	docker build --tag=${user}/${repository}:${version} .

push:
	docker push ${user}/${repository}:${version}

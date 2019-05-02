# docker-grow-backend
Docker container for bulding our grow-backend codebase

# To Test:

`docker build --no-cache .`

# To deploy:

-Create a git tag like "v5.5"
-Push the tag
-A build will be created at: https://cloud.docker.com/u/poweredbygrow/repository/docker/poweredbygrow/docker-grow-backend/builds
-You can then use it by referencing: docker-grow-backend:v5.5

# AspnetCore Docker Versioning Exercise
- docker image build -t endorupgrade .
- docker run -p 5001:80 --rm endorupgrade:latest --network=host

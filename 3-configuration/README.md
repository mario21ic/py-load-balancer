# py-load-balancer

```
conda create -n pylb python=3.9
conda activate pylb
pip install -r requirements.txt
```

Running Tests:
```
docker build -t mario21ic/pylb ./
docker-compose up -d

curl localhost:8081
curl localhost:8082

curl localhost:9081
curl localhost:9082

docker-compose down

make test
```

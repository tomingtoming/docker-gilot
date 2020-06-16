# docker-gilot
docker image for [gilot](https://github.com/hirokidaichi/gilot)

## Usage
```
docker run -v `pwd`:/app tomingtoming/gilot bash -c 'gilot log /app > /app/repo.csv'
docker run -v `pwd`:/app tomingtoming/gilot bash -c 'gilot plot -i /app/repo.csv -o /app/repo.png'
```

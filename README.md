# docker-gilot
docker image for [gilot](https://github.com/hirokidaichi/gilot)

## Usage
```bash
docker run -v REPO_DIR:/app tomingtoming/gilot bash -c 'gilot log /app > /app/repo.csv'
docker run -v REPO_DIR:/app tomingtoming/gilot bash -c 'gilot plot -i /app/repo.csv -o /app/repo.png'
```

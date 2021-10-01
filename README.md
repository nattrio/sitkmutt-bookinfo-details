# sitkmutt-bookinfo-details

Detail service has been developed on Ruby

## License

MIT License

## How to run

```bash
ruby details.rb 8081
```

## How to run with Docker

```bash
# Build Docker Image for detail service
docker build -t details .

# Run ratings service on port 8080
docker run -d --name details -p 8081:8081 details
```

## How to run with Docker Compose

```bash
docker-compose up
```

## Website

[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)
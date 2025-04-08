# mailcast-Gal

## Start Here
Creating an email parser using Golang and OAuth 2.0 for Google involves the following steps :

- Enable Gmail API in Google Cloud Console
- Go to the Google Cloud Console.
- Create a new project or select an existing one.
- Enable the Gmail API under APIs & Services.
- Configure OAuth consent screen (set up user type and scopes).
- Create OAuth 2.0 credentials (Client ID & Secret).
- Download the credentials.json file.


## Development

Please install or update your golang version to  1.21 or latest

Please follow this command step by step :

```
go mod init mailcast-gal
go mod tidy
go run .
go run cmd/main.go
```

## Docker

Please follow this command step by step :

```
docker build -t mailcast-gal .
docker run -e GO_ENV=development -p 7070:8080 mailcast-gal:latest
```


## Git Dependency

- [Get started with asynqmon](https://github.com/hibiken/asynqmon)
- [Get started with asynq](https://github.com/hibiken/asynq)
# Go book API

## Prerequisite
- Installing Make


## Commands
- Run DB: `docker-compose up`
- Run app: `make start`
- Stop app: `make stop`
- Test: `go test -v ./cmd/api.`
- Coverage: `#cd cmd/api go test -coverprofile=coverage.out && go tool cover -html=coverage.out`
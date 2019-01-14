
Basic REST API to manage movies written in Go and uses MongoDB as storage

## How to use
    Fetch dependencies
        go get github.com/BurntSushi/toml gopkg.in/mgo.v2 github.com/gorilla/mux
    Clone Repo
        git clone https://github.com/mir-nawaz/golang-tutorials
    Run
        go run main.go



## API Details

![API Details](API-Details.png)

## Movies Model
    name: string
    description: string
    cover_image: string

## Structure
    .
    ├── API-Details.png
    ├── config
    │   └── config.go
    ├── config.toml
    ├── dao
    │   └── movies.go
    ├── main.go
    ├── models
    │   └── movie.go
    └── README.md


[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)

# go-microservice

[![Go Report Card](https://goreportcard.com/badge/github.com/Hamedblue1381/go-microservice)](https://goreportcard.com/report/github.com/Hamedblue1381/go-microservice)

`go-microservice` is a minimal and lightweight template for building microservices using Go. This repository serves as a starting point for developers looking to create efficient and scalable microservices with Go.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Requirements

- [Go](https://golang.org/doc/install) 1.16 or later

## Installation

1. Clone the repository:

   ````bash
   git clone https://github.com/Hamedblue1381/go-microservice
   cd go-microservice
   ```

2. Install the required Go dependencies:

   ````bash
   go mod tidy
   ```

## Usage

1. Run the microservice:

   ````bash
   go run main.go
   ```

2. The microservice will start on the default port (8080). You can change the port in the `main.go` file.

3. Use a tool like [Postman](https://www.postman.com/) or [curl](https://curl.se/) to send HTTP requests to the microservice and test its functionality.


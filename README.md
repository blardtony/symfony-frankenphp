# Symfony with Frankenphp

This is a simple example of how to use Symfony with Frankenphp.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone this repository
2. Run `make start` to build and start the containers
3. Access the application at `http://localhost:8080`


## Available Make commands

Run `make` to see all available commands.

## Services

- PHP: FrankenPHP container
- Database: PostgreSQL
- Mailer: Mailpit for email testing

## Development

- The application code is mounted in the PHP container at `/app`
- Xdebug is available and can be enabled by setting `XDEBUG_MODE` environment variable

## Database

- PostgreSQL is accessible on port 5432
- Database credentials are set via environment variables
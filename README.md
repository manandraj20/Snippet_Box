# Full-stack Go

This is the final code for `Snippetbox` website. It's a full-stack Go web application called "Snippetbox" that lets users CRUD text snippets (similar to GitHub gists).

<img width="500" src="./lets-go-screenshot.png" />

### Features

- Authentication. Users can register and sign in.
- Protected endpoints. Only signed-in users can create snippets.
- RESTful routing.
- Middleware.
- MySQL database.
- SSL/TLS web server using HTTP 2.0.
- Generated HTML via Golang templates.
- CRSF protection.

### Development

##### `go run cmd/web/*`

Starts the local web server with HTTPS on port 4000 ([https://localhost:4000](https://localhost:4000))

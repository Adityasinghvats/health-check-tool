# health-check-tool
- A simple CLI based healthcheck tool for your web services.
Tells you about whether your service is running or not using terminal.

- Personally, I have been using it to keep an eye my sensor servers for my new weather station project, because cloud providers would spin down the server in case of long inactivity.

## Start using it
- Prerequisites
  - Go 1.23 or higher
  - Any code editor
- Get the repo
```bash
git clone https://github.com/Adityasinghvats/health-check-tool.git
```
- Get into the directory
```bash
cd health-check-tool
```
- Get all dependencies
```bash
go mod tidy
```
- Run your programme using the terminal
```bash
$go run . --domain https://tailwindcss.com/
```
- For specifying port you can use flag `--port`
```bash
$go run . --domain https://localhost --port 8080
```
## Demo
![Screenshot 2025-03-29 171312](https://github.com/user-attachments/assets/28576e9f-958b-4de1-8997-1f5f3d2b8d47)

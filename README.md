# Github-Actions-AK
Aim : Continous integration and Continous deployment

This is a simple Node.js Express application running in Docker, managed by Docker Compose, and automated through GitHub Actions.

Steps:
1. Local code commit
2. On PUSH event triggers -> CiCd
3. SSH into the server
4. cd into the workdir
5. PULL the latest code
6. Run the compose yaml

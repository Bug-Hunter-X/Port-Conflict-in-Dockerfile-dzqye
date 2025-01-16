# Dockerfile Port Conflict Bug

This repository demonstrates a common error in Dockerfiles: port conflicts. The original `Dockerfile` attempts to use port 3000, which may already be in use. The solution involves identifying and resolving the port conflict.
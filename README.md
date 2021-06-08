# MusicShar Meta Project

This is the meta project for the open-source MusicShar project. It includes the required documentation and configuration to develop and deploy the MusicShar solution!
## What is MusicShar?
MusicShar is an open-source, collaborative virtual party platform allowing users to connect in real-time and watch content together.

## MusicShar Components
The application is comprised of a few key component and systems:
- `frontend` -  Built in JavaScript using React, holding the interactivity and functionality for the application.
- `backend` - The back-end API utilised by the front-end via HTTP calls. Also exposes web socket communication for real-time interactivity.
 
https://github.com/DanTheDJ/musicshar-frontend - front-end repository
https://github.com/DanTheDJ/musicshar-backend - back-end repository

## Development Environment
Docker can be used to rapidly setup a development environment. This includes the PostgreSQL DBMS, a Redis instance, and the adminer web interface for inspecting the PostgreSQL database. A `docker-compose.yml` file can be found within this repository.

## Hosting Requirements
In order to host MusicShar, the following requirements must be met:
- Available DBMS (tested with PostgreSQL)
- Redis cache server for session storage.
- Docker installation - The `frontend` and `backend` both contain a `Dockerfile` with steps to compile the application into it's production version. The build Docker images can be operated.


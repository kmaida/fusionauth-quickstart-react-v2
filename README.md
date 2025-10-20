# FusionAuth React Quick Start

See the [FusionAuth React Quick Start documentation here](https://fusionauth.io/docs/quickstarts/quickstart-javascript-react-web).

This repository contains setup for a locally-hosted FusionAuth authorization server that runs in a Docker container and a simple [Vite](https://vite.dev) [React](https://react.dev) app using [FusionAuth](https://fusionauth.io/docs) for authentication and authorization.

## Dependencies

* [Node.js](https://nodejs.org/en/download) v22+
* [Docker](https://docs.docker.com/get-started/get-docker/) v23+

If you prefer, you can use a free Docker Desktop alternative:

* [OrbStack](https://orbstack.dev/) for Mac
* [Podman](https://podman.io/) for PC (you will need to replace the `docker [command]` command keyword with `podman [command]`)

Clone this repository.

## Install FusionAuth

1. From the `/fusionauth` directory, run the following Docker compose command: `docker compose up -d`
2. After the compose process is successful, you can access FusionAuth in your browser at [http://localhost:9011/admin](http://localhost:9011/admin)
3. You can log into your FusionAuth admin dashboard with the username `admin@example.com` and the password `password`

## Set up the React app

1. From the `/fusionauth-quickstart-react` folder, run the following command: `npm install`
2. To start the React app, run `npm run dev`
3. The app will be accessible in the browser at [http://localhost:3000](http://localhost:3000)
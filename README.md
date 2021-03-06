# Awesome TODO

Quickly written TODO app (to demonstrate dockerization).

## Getting Started

1.  Install [Docker](https://docs.docker.com/get-docker/)

1.  Install [Make](https://www.gnu.org/software/make/) (you probably already have it)

1.  _(Optional) Login to [GitHub container registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry#authenticating-to-the-container-registry) (to make use of cached Docker images)_

1.  Start project

    ```shell
    $ make up
    ```

1.  Go to app

    http://localhost:3001

1.  Configure via variables defined in `Makefile`

## Libraries

### Frontend
- Boilerplate Generator - [`create-react-app`](https://create-react-app.dev/)
- Styling - [`styled-components`](https://styled-components.com/)
- Base Styles - [`@picocss/pico`](https://picocss.com/)
- GraphQL Client - [`@apollo/client`](https://www.apollographql.com/docs/react/)

### Backend
- Boilerplate Generator - [`create-fastify`](https://github.com/fastify/create-fastify)
- Data Models - [`mongoose`](https://mongoosejs.com/)
- GraphQL Adapter - [`mercurius`](https://mercurius.dev/#/)
- Config Management - [`config`](https://github.com/lorenwest/node-config)

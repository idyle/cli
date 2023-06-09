# idyle/cli

idyle's Command Line interface (CLI) for system and service deployments. 

## Setup

### Environment Variables

The variables below require idyle's internal configurations. Authorization will be needed to access this information.

```
GOOGLE_APPLICATION_CREDENTIALS=
IDYLE_CLI_PROJECT_NAME=
IDYLE_CLI_DEFAULT_LOAD_BALANCER=
IDYLE_CLI_DEFAULT_BUCKET=
IDYLE_CLI_DEFAULT_LOCATION=
```

### Installation

`npm install -g`

Aside from installing library dependencies, using the `-g` flag installs the CLI itself on the local system. All commands are accessible with the `idyle` prefix.

## Commands

### Frontends (Static Hosting)

`idyle {service} frontend create`

Creates a new frontend based on a service name.

`idyle {service} frontend update`

Updates a frontend based on an existing service.

### Backends (Dynamic Hosting)

`idyle {service} backend create`

Creates a new backend based on a service name.

`idyle {service} backend update`

Updates a backend based on an existing service.

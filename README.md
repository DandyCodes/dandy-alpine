# Dandy Apline

A template repository for bare-bones development environments within Visual Studio Code.

# Installation

1. Create a new repository using this template.

1. Install the 'Dev Containers' Visual Studio Code extension.

1. Open the command palette:
- Mac:

    ```Cmd + Shift + P```

- Windows/Linux:

    ```Ctrl + Shift + P```

- Run the command:

    ```Dev Containers: Clone Repository in Container Volume```

- Enter the URL of your newly created repository to clone it:

    ```https://github.com/<user>/<repo>```

4. Add any packages you wish to install in the Dockerfile:

    ```Dockerfile
    # RUN apk add nodejs npm yarn
    # RUN apk add poetry
    # RUN apk add go gopls
    ```
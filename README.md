# github-actions-packages
![clojars](https://img.shields.io/clojars/v/github-actions-packages/lein-template.svg)

A Leiningen template for deploying a library to github packages. Namely used
 for deploying private packages in a private repository. No configuration is 
 required as github handles the github actor and token authentication from 
  github actions.

## Usage

Use the fully qualified name including the username/organization of your repo
```.sh
lein new github-actions-packages username/project
```

The repo also includes a PR test checker with github actions


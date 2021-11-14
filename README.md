## Tutorial followed to create the basis of this repo:

`https://golang.org/doc/tutorial/web-service-gin`

# To get dependencies

```sh
sudo go get .
```

# To run the server without hot reloading:

```sh
sudo go run .
```

# To run with hot-reloading:
### first install node then npm i -g nodemon

#### then

```sh
nodemon -e go --signal SIGTERM --exec 'go' run .
```

#### OR

```sh
sh dev.sh
```

#### OR

### add an alias to your .zshrc or .bash_profile then restart the terminal:

```sh
alias dev='sh dev.sh'
```

### then type this to start the server with hot-reloading in the terminal in the root directory of this repo:

```sh
dev
```


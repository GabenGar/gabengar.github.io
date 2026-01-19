# GabenGar.github.io

## Develop

### Clone the project

```sh
git clone --recurse-submodules https://github.com/GabenGar/GabenGar.github.io.git
git submodule update --init --recursive
```

### Update the state of remotes

```sh
git submodule update --remote
```

After pull:
```sh
git submodule update --init --recursive
```

### Set up push url for a submodule

```sh
git config submodule.todos.pushurl <PRIVATE_URL>
```

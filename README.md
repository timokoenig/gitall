# gitall
Execute git commands over all repositories in current directory

### Usage
```sh
$ gitall [-v | --branch | --name] {help | * | update | deintegrate | clean}
```

##### Show git status

```sh
$ gitall
```

##### Update all repositories (fetch, pull, remove merged and deleted branches)

```sh
$ gitall update
```

##### Deintegrate CocoaPods in all repositories

```sh
$ gitall deintegrate
```

##### Checkout branch in repositories

```sh
$ gitall checkout feature/example
```

##### Execute git pull command on repositories with specific branch

```sh
$ gitall --branch feature/example pull
```

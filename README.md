# furthermore

Interim censeo, Carthago delenda est. She is a menace to Rome.

`furthermore` is a command-line tool that manipulates keys in an etcd server or cluster somewhere over there. It's meant to be more convenient than `etcdctl`.

It uses a file named ~/.etcdrc` for config. That file looks like this:

```ini
hosts=my-etcd-host.example.com:443
ssl=true
```

Usage:

```
furthermore: manipulate keys on a remote etcd server

Commands:
  del <key>          remove a key
  get <key>          get the value for a key
  ls <dir>           get a directory listing
  mkdir <dir>        create the named directory, recursively
  rmdir <dir>        remove the named directory
  set <key> <value>  set a key to a new value

Options:
  --version  Show version number                                       [boolean]
  --help     Show help                                                 [boolean]
```

## License

ISC

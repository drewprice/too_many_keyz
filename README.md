To use this, just clone it and add a `.env` file in the root that looks like

```shell
export USERNAME=<github-username>
export TOKEN=<github-access-token>
```

then run

```
$ ./killemzkeyz
```

You can generate an access token at https://github.com/settings/tokens


(Also, this may or may not result in an infinite loop... if you feel like it's gone on for far too long, prolly just interrupt it.)


# gacp
Git add/commit/push

This is just a shell script that replaces

```sh
git add .
git commit -m "message"
git push
```

with a single command.

```sh
gacp "commit message"
```

Use with care, there are times when you want to be a bit more selective.  Also leave good commit messages.

# installation
You can copy gacp to `/usr/local/bin` on mac to make it a global command.

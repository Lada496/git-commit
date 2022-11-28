how to create env depentent alias

1. install and set up direnv
2. `touch .envrc`
3. modify .envrc to put alias (you have to export a function as direnv doesn't support alias)
4. Run `direnv allow` to approve its content

reference:

- how to create an alias with direnv: https://github.com/direnv/direnv/issues/73#issuecomment-1242969787
- how to install direnv: https://direnv.net/docs/installation.html

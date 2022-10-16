# Dev-Cheat-Sheet

Cheat sheet for commands

## Useful articles:

1. [Migrate from HTTPS clone to SSH](https://stackoverflow.com/questions/57230972/how-to-migrate-from-https-to-ssh-github)
2. [Start a PostgreSQL server on Mac](https://dataschool.com/learn-sql/how-to-start-a-postgresql-server-on-mac-os-x/)
3. [PostgreSQL Medium article for terminal commands](https://medium.com/@xueyingli66/start-using-postgresql-with-terminal-on-mac-787ab643c817)
4. [Morgan logger npm package for Express.js servers](https://www.npmjs.com/package/morgan)
5. [Simple Express server setup](https://expressjs.com/en/starter/hello-world.html)

## Git Commands

###### Push changes

```
git status
git add . || git add "FILE NAME"
git commit -m "YOUR TEXT HERE"
```

###### Resolving Merge Conflicts

Steps:

1. run a status check to confirm in local branch is behind Main
2. If local is behind remote

   ```
   git fetch
   ```

3. Confirm conflicts via terminal log and resolve conflicts in editor
4. Merge changes with git merge || VS Code UI
5. Stage, commit and push to Main

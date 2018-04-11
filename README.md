# git Grundlagen

## Arbeiten mit Remote-Repositories

### add remote git repository
```git remote add <name> <url>```

### and then push using the remote name
```git push <name>```
```git remote add snackmachine https://github.com/aguetler25/ccc_snackmachine```

### Ueberpruefen der Einstellungen
```
git remote -v
snackmachine    https://github.com/aguetler25/ccc_snackmachine (fetch)
snackmachine    https://github.com/aguetler25/ccc_snackmachine (push)
```

### Und auf das Remote-Repository "pushen"
```git push --set-upstream snackmachine master```

Branch 'master' set up to track remote branch 'master' from 'snackmachine'.
```C:\Users\guetler\eclipse-workspace\CCCSnackMachine\src (master -> snackmachine)```

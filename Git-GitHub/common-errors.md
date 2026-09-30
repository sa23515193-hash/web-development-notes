# Common Git and GitHub Errors

## Remote already exists

Check existing remotes:

```bash
git remote -v
```

Change the URL if needed:

```bash
git remote set-url origin REPOSITORY_URL
```

## Rejected push

First inspect the remote state:

```bash
git pull --rebase origin main
```

Then push again:

```bash
git push
```

## Authentication

If GitHub asks for authentication, use the supported GitHub authentication method rather than placing passwords inside repository URLs.

[Deprecated]
# buildpacks-aria2

Heroku Build-Pack for Aria2.
Always up-to-date with the latest static build link from the official repo.
Suitable for Mirror Bots.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/jagrit007/buildpacks-aria2.git
```

Or run the following from the Heroku command line:

```
heroku buildpacks:add https://github.com/jagrit007/buildpacks-aria2.git
```

## Aria Changelogs:

- *v1.35.0*
```bash
Bug fixes.
Updated expat to v2.2.6.
Updated sqlite3 to v3.30.0.
Updated c-ares to v1.15.0.
Updated OpenSSL to v1.0.2t.
```

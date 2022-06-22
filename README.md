# Credential helper for Docker, storing the creds in LastPass

See [docker documentation on credential stores](https://docs.docker.com/engine/reference/commandline/login/#credentials-store)
for more information.

The short version is: put the script in your `$PATH` and add the
following to your `~/.docker/config.json`:
```json
{
	"credsStore": "lastpass"
}
```

## Dependencies

This script requires [`lastpass-cli`](https://github.com/lastpass/lastpass-cli)
(obviously), as well as [`jq`](https://stedolan.github.io/jq/).

## License

This repository and all of its contents are distributed under terms of
the MIT license.

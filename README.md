A minimalist Deno project template with [Undici](https://github.com/nodejs/undici), the Node.js project's HTTP client.

## Run

```sh
deno task start
```

The example makes an HTTPS request to `example.com`, so it needs network access.

## Security

Dependencies are declared in `package.json` and managed by Deno. Dependabot checks npm dependencies weekly using `.github/dependabot.yml`. To receive security alerts, enable Dependabot alerts in the repository's GitHub settings.

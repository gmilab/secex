# Secure script auto-execution pipeline

## Setup
Generate (or use an existing GPG signing key).

```bash
$ gpg --gen-key
$ gpg --armor --export "[your key id]"
```

## Deploying new scripts
```bash
$ secex_sign myscript.sh
```

## Automatic execution
```bash
$ secex_execute https://url/to/myscript.sh
```


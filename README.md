# Stack Templates

My opinionated Haskell Stack templates, to be used with `stack new`

# Usage

In a shell with `stack` executable present:

```bash
$ stack new <appname> saeidscorp/<template>
```

For example:

```bash
$ stack new --resolver lts-24.0 my-awesome-app saeidscorp/stack-nix
```

> [!TIP]
> You can add a flag in the generated `stack.yaml` for GHC to rebuild files when there are GHC flag changes:
> `rebuild-ghc-options: true`

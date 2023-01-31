# Setup pnpm Action

Reduce boilerplate when installing setting up Node.js and installing
[pnpm](https://pnpm.io) dependencies.

## Usage

```yaml
- uses: mskelton/setup-pnpm@v1
```

## Checkout a specific Git ref

```yaml
- uses: mskelton/setup-pnpm@v1
  with:
   ref: ${{ github.head_ref }}
```

## Specify Node version

```yaml
- uses: mskelton/setup-pnpm@v1
  with:
   node-version: '18.x'
```

## Pass additional flags to the install command

```yaml
- uses: mskelton/setup-pnpm@v1
  with:
   flags: --prod
```

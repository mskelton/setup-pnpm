# Setup pnpm Action

Reduce boilerplate when installing setting up Node.js and installing
[pnpm](https://pnpm.io) dependencies.

## Usage

```yaml
- uses: mskelton/setup-pnpm@v2
```

## Checkout a specific Git ref

```yaml
- uses: mskelton/setup-pnpm@v2
  with:
   ref: ${{ github.head_ref }}
```

## Specify Node version

```yaml
- uses: mskelton/setup-pnpm@v2
  with:
   node-version: '18.x'
```

## Customize fetch depth

```yaml
- uses: mskelton/setup-pnpm@v2
  with:
   fetch-depth: 0
```

## Pass additional flags to the install command

```yaml
- uses: mskelton/setup-pnpm@v2
  with:
   flags: --prod
```

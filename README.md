# Reproduction for bug "SvelteKit: build fails with 'Unknown file extension .svelte'" 

## Steps to reproduce the issue

```bash
pnpm i
pnpm build
pnpm run preview
```

## Expected result

No error.

## Actual result

The following error message:
```
Unknown file extension ".svelte" for (...)/node_modules/.pnpm/atropos@1.0.1/node_modules/atropos/svelte/atropos-svelte.svelte

TypeError [ERR_UNKNOWN_FILE_EXTENSION]: Unknown file extension ".svelte" for (...)/node_modules/.pnpm/atropos@1.0.1/node_modules/atropos/svelte/atropos-svelte.svelte
```
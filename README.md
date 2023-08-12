# Cache

By default, GitHub Actions cache is not supported for tags. This means that if you have a workflow that runs only on tags, you cannot use cache actions in that workflow. However, you can enable caching for tags by adding the tags key to the on section of your workflow file and specifying the tag pattern you want to cache.

```bash
pnpm run build
```

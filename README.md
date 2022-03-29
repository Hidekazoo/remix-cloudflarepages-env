# Using Environment Variables in Local Development

## Change from default settings

- Add `--binding $(cat .env)` to dev:wranger in package.json
- Add loader function and useLoaderData to component

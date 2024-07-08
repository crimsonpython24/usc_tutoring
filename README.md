# usc_tutoring

## Development Rules

- Please use `pnpm` to install all packages so that they and their dependencies are indexed correctly (especially happens in updating mutual dependencies)
  - I.e., use `pnpm install { package }` and `pnpm install --save-dev { package }`
  - If a package is only used for development (e.g., unit-testing tools, linters) and doesn't affect production, use `--save-dev` for devDependencies instead
- Please update `.eslintrc.yml` and `.prettierrc` if the current settings are outdated, inconvenient for development, look bad, or anything else

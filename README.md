# Nitro Github Preset nojekyll Bug

**Bug description**: `.nojekyll` file is not generated when running `pnpm generate`

**Repro Steps**:

- run `pnpm generate`
- inside the `.output/public` folder the `.nojekyll` is missing

However running `pnpm build` works, in this case the `.nojekyll` file is being generated.

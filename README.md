# xVOWL Landing page

Landing page for xvowl.

## Development

```bash
pnpm i

pnpm exec hugo version
# Make sure that you have the version ...+extended in the output if not do following workaround

rm -rf node_modules/hugo-bin/vendor
pnpm exec node ./node_modules/hugo-bin/lib/install.js

```

## Credits

https://github.com/tomowang/hugo-theme-tailwind


## Cloudflare publishing

Production uses native Cloudflare Git builds from `gh-pages`. Run `npm ci`
and `npm run check:deploy` to validate the explicit public assets directory.
Build with `npm run build` and deploy with `npm run deploy`. Cloudflare holds
deployment credentials; the original Pages branch and source history remain
recovery sources. The revision is at `/.well-known/cloudflare-build.json`.

## License

Original site code and documentation by Dean Pierce are licensed under the [Apache License 2.0](LICENSE).
The pre-existing GitHub Pages theme assets in `stylesheets/`, including normalize.css, are third-party material and are excluded from this grant; their existing licenses and notices remain unchanged. External dependencies and linked assets retain their respective terms.

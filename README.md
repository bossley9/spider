# Spider

A static site generator written in Deno TypeScript.

## Why "spider"?

Because spiders create **web**s...

## Roadmap

- [ ] no non-reproducible dependencies. Don't use NPM packages or vendor them (make sure they match the licensing).
- [ ] support TypeScript always.
- [ ] statically generate HTML pages from React/Preact (or similar JSX) templating, including composable components.
- [ ] generate HTML files based on the filesystem structure, similar to [NextJS's pages router](https://nextjs.org/docs/pages/building-your-application/routing).
- [ ] support FastCGI via PHP files.
- [ ] create a live-reloading web server.
- [ ] minify generated HTML files and enable automatic GZIP compression.
- [ ] support reading or parsing static files during compilation.
- [ ] statically generate other file formats similar to [Astro's endpoints](https://docs.astro.build/en/core-concepts/endpoints/).
- [ ] no JS shipped to the client by default unless inline scripts are added to the HTML markup.
- [ ] parse and convert Markdown files to HTML via some mechanism (TBD).

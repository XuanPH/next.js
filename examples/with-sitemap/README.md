# With Sitemap example

This example shows how to generate a `sitemap.xml` file based on the pages in your [Next.js](https://nextjs.org/) app. The sitemap will be generated and saved in the `public` directory after starting the development server or by making a build.

## Deploy your own

Deploy the example using [Vercel](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/next.js/tree/canary/examples/hello-world)

## How to use

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-sitemap with-sitemap-app
# or
yarn create next-app --example with-sitemap with-sitemap-app
```

### Download manually

Download the example:

```bash
curl https://codeload.github.com/vercel/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/with-sitemap
cd with-sitemap
```

Install it and run:

```bash
npm install
npm run dev
# or
yarn
yarn dev
```

Your app should be up and running on [http://localhost:3000](http://localhost:3000) and the sitemap should now be available in [http://localhost:3000/sitemap.xml](http://localhost:3000/sitemap.xml)! If it doesn't work, post on [GitHub discussions](https://github.com/vercel/next.js/discussions).

To change the website URL used by `sitemap.xml`, open the file `.env` and change the `WEBSITE_URL` environment variable:

```bash
# Used to add the domain to sitemap.xml, replace it with a real domain in production
WEBSITE_URL=https://my-domain.com
```

Deploy it to the cloud with [Vercel](https://vercel.com/import?filter=next.js&utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).

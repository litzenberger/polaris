# Contribute to Polaris

# Code

Code contributions are accepted back to Polaris, please make an issue to discuss your change first.

# Documentation

We welcome documentation contributions. Our documentation can be viewed live at [https://nf-polaris.netlify.app/#/][docs].

## Run the Documentation Locally

Our documentation is run by serving the docs folder at a given port.

From the root folder on a command console, enter the command:

```sh
npm run start:docs
```

This displays the following:

```sh
> polaris@x.y.z doc:serve /path/to/your/repo/polaris
> docsify serve -p 4000 docs

Serving /path/to/your/repo/polaris/docs now.
Listening at http://localhost:4000
```

The documentation is served on `localhost:4000`.

### Serve in Other Ways

Our documentation builds on the fly. All you need to do is serve the docs folder. Any program or CLI tool used for serving a folder works - **as long as it can handle hash routing**.

Another popular module to serve files is `serve` on npm. To run, with hash router support, enter the command:

```sh
npx serve -s -l 4000 docs
```

This displays the following:

```sh

  Serving!

  - Local:            http://localhost:4000
  - On Your Network:  http://192.168.1.60:4000

  Copied local address to clipboard!

```

The documentation is served on `localhost:4000` in this case.

<!--- [docs]:nearform.github.io/polaris --->

[docs]: https://nf-polaris.netlify.app/#/

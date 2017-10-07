# [Tiksgiving.com](https://tiksgiving.com/)

Enjoy tiki-themed cocktails for Thanksgiving!

**[Load _Tiksgiving.com_ now](https://tiksgiving.com/)!


## Development

First, clone [this Git repository](https://github.com/tiksgiving/tiksgiving.com)

```sh
mkdir -p tiksgiving && cd tiksgiving
git clone git@github.com:tiksgiving/tiksgiving.com.git && cd tiksgiving.com
```

Then, install the [Node](https://nodejs.org/en/download/) dependencies:

```sh
npm install
```

To start the local Node development server:

```sh
npm start
```

All of the web content is static (see the [`public_html` directory](https://github.com/tiksgiving/tiksgiving.com/tree/master/public) directory).

To serve the site from the local development server (which includes in-browser live reloading for rapid development):

```sh
npm run dev
```

Then launch the [local site](http://localhost:8080/) from your favourite browser:

[__http://localhost:8080/__](http://localhost:8080/)

If you wish to serve the site from a different port:

```sh
PORT=8000 npm run dev
```


## Deployment

In production, the server is run like so:

```sh
npm run prod
```

To reproduce the production server locally using Heroku's [`foreman`](https://devcenter.heroku.com/articles/procfile):

```sh
foreman start web
```


## Contributing

[Contributions are very welcome!](CONTRIBUTING.md)


### License

All code and content within this source-code repository, including all contributions, are licensed under the [**Creative Commons Zero v1.0 Universal** license (CC0 1.0 Universal; Public Domain Dedication)](LICENSE.md).

You can copy, modify, distribute, and perform this work, even for commercial purposes, all without asking permission.

For more information, refer to these following links:

* a copy of the [license](LICENSE.md) in [this source-code repository](https://github.com/tiksgiving/tiksgiving.com)
* the [human-readable summary](https://creativecommons.org/publicdomain/zero/1.0/) of the [full text of the legal code](https://creativecommons.org/publicdomain/zero/1.0/legalcode)
* the [full text of the legal code](https://creativecommons.org/publicdomain/zero/1.0/legalcode)

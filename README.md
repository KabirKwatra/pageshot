# big-pageshot [![][now-deploy-src]](#deploy)

Pageshot as a service but bigger.

## Usage

- __Web UI__: https://bigshot.now.sh
- __Endpoint__: https://bigshot.now.sh/shot

Examples:

- https://bigshot.now.sh/shot?url=https://google.com
- https://bigshot.now.sh/shot?url=https://github.com&full=true

Query Params:

- __`url`__: The webpage location. (required)
- __`width`__: Viewport width. (default: 1280)
- __`height`__: Viewport height. (default: 800)
- __`full`__: Full page screenshot. (default: false)
- __`dpr`__: Device pixel ratio. (default: 2)

## Deploy

- to [now.sh](https://zeit.co/now):
```
now KabirKwatra/pageshot
```

- using [Dockerfile](Dockerfile):
```
docker pull KabirKwatra/pageshot
```

- running locally (require Google Chrome installed):
```
npm start
```

## License

[pageshot by Amio](https://github.com/amio/pageshot)

ISC © [Amio](https://github.com/amio)

[now-deploy-src]: https://badgen.net/badge/%E2%96%B2/$%20now%20amio%2Fpageshot/333

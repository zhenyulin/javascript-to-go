# javascript-to-go

cheatsheet to help Javascript developers picking up Go by providing a map of equivalence

> packages listed here are not necessary the best in its kind but typical ones, suggestions are welcome

## general toolings

|          category           |      javascript       |         go        |
|-----------------------------|-----------------------|-----------------------|
| package manager | [npm](https://github.com/npm/cli) | [go tool](https://github.com/golang/tools) |
| code linter | [eslint](https://github.com/eslint/eslint) | [golint](https://github.com/golang/lint) |
| code formatter | [prettier](https://github.com/prettier/prettier) | [go fmt](https://blog.golang.org/go-fmt-your-code) |
| static type checker | [flow](https://github.com/facebook/flow) | [go type](https://golang.org/x/tools/cmd/gotype) |
| unit test runner | [jest](https://github.com/facebook/jest) | [go test](https://blog.alexellis.io/golang-writing-unit-tests/), [testing](https://golang.org/pkg/testing/) |
| mock | [jest](https://github.com/facebook/jest) | [mock](https://godoc.org/github.com/stretchr/testify/mock) |
| logger | [winston](https://github.com/winstonjs/winston) | [go-logging](https://github.com/op/go-logging) |
| tracing | | |
| benchmark | | |
| git commit hook | [husky](https://github.com/typicode/husky)/[pre-commit](https://github.com/observing/pre-commit) | |
| docs | | |

## web framework and toolings

|          category           |      javascript       |         go        |
|-----------------------------|-----------------------|-----------------------|
| runtime | [Chrome V8](https://developers.google.com/v8/) | [Go Runtime](https://golang.org/pkg/runtime/) |
| web server | [node](https://github.com/nodejs/node) | [go net/http](https://golang.org/pkg/net/http/) |
| http server | [express](https://github.com/expressjs/express) | [echo](https://github.com/labstack/echo), [iris](https://github.com/kataras/iris) |
| http client | [node-fetch]() | [go net/http](https://golang.org/pkg/net/http/), [go http-client](https://github.com/ddliu/go-httpclient) |
| live reload | [webpack]()  | [gin](https://github.com/codegangsta/gin) |
| i18n i10n | | |
| graphql toolkit | [apollo-server](https://github.com/apollographql/apollo-server), [graphql-tools](https://github.com/apollographql/graphql-tools) | [graphql-go](https://github.com/graph-gophers/graphql-go) |


## syntax

[Go for Javascript Developer](http://www.pazams.com/Go-for-Javascript-Developers/)
[From Node to Go](https://tech.xogrp.com/from-node-to-go-a-high-level-comparison-56c8b717324a)

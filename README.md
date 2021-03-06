# http-middlewares

http middleware fot net/http

[![GoDoc](https://godoc.org/github.com/thinkgos/http-middlewares?status.svg)](https://godoc.org/github.com/thinkgos/http-middlewares)
[![Go.Dev reference](https://img.shields.io/badge/go.dev-reference-blue?logo=go&logoColor=white)](https://pkg.go.dev/github.com/thinkgos/http-middlewares?tab=doc)
[![Build Status](https://travis-ci.org/thinkgos/http-middlewares.svg)](https://travis-ci.org/thinkgos/http-middlewares)
[![codecov](https://codecov.io/gh/thinkgos/http-middlewares/branch/master/graph/badge.svg)](https://codecov.io/gh/thinkgos/http-middlewares)
![Action Status](https://github.com/thinkgos/http-middlewares/workflows/Go/badge.svg)
[![Go Report Card](https://goreportcard.com/badge/github.com/thinkgos/http-middlewares)](https://goreportcard.com/report/github.com/thinkgos/http-middlewares)
[![Licence](https://img.shields.io/github/license/thinkgos/http-middlewares)](https://raw.githubusercontent.com/thinkgos/http-middlewares/master/LICENSE)
[![Tag](https://img.shields.io/github/v/tag/thinkgos/http-middlewares)](https://github.com/thinkgos/http-middlewares/tags)
## middleware

- [authj](#authj) is an authorization middleware, it's based on [casbin](https://github.com/casbin/casbin)
- [gzap](#gzap) is gzap provides log handling using zap package.
- [nocache](#nocache) noCache is a simple piece of middleware that sets a number of HTTP headers to prevent a router (or subrouter) from being cached by an upstream proxy and/or client.
- [requestid](#requestid) is a middleware that injects a request ID into the context of each request.
- [traceid](#traceid) traceid is a middleware that injects a trace ID into the context of each request. A trace ID is a string of uuid.

## [mids](#mids)
helper

## Donation

if package help you a lot,you can support us by:

**Alipay**

![alipay](https://github.com/thinkgos/thinkgos/blob/master/asserts/alipay.jpg)

**WeChat Pay**

![wxpay](https://github.com/thinkgos/thinkgos/blob/master/asserts/wxpay.jpg)
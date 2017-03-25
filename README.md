# api documentation for  [restify (v4.3.0)](http://restifyjs.com)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-restify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-restify)
#### REST framework

[![NPM](https://nodei.co/npm/restify.png?downloads=true)](https://www.npmjs.com/package/restify)

[![apidoc](https://npmdoc.github.io/node-npmdoc-restify/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-restify_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-restify/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-restify/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Mark Cavage",
        "email": "mcavage@gmail.com"
    },
    "bin": {
        "report-latency": "./bin/report-latency"
    },
    "bugs": {
        "url": "https://github.com/restify/node-restify/issues"
    },
    "contributors": [
        {
            "name": "Adam Argo"
        },
        {
            "name": "Alex Liu"
        },
        {
            "name": "Andrew Robinson"
        },
        {
            "name": "Andrew Sliwinski"
        },
        {
            "name": "Armin Tamzarian"
        },
        {
            "name": "Ben Doerr"
        },
        {
            "name": "Ben Hale"
        },
        {
            "name": "Ben Howes"
        },
        {
            "name": "Ben Hutchison"
        },
        {
            "name": "Brian Pin"
        },
        {
            "name": "Bryan Donovan"
        },
        {
            "name": "Colin O'Brien"
        },
        {
            "name": "Corbin Uselton"
        },
        {
            "name": "Diego Torres"
        },
        {
            "name": "Domenic Denicola"
        },
        {
            "name": "Domikik Lessel"
        },
        {
            "name": "Dominic Barnes"
        },
        {
            "name": "Erik Kristensen"
        },
        {
            "name": "Falco Nogatz"
        },
        {
            "name": "Gergely Nemeth"
        },
        {
            "name": "Guillaume Chauvet"
        },
        {
            "name": "Isaac Schlueter"
        },
        {
            "name": "Jonathan Dahan"
        },
        {
            "name": "Josh Clulow"
        },
        {
            "name": "Matt Smillie"
        },
        {
            "name": "Micah Ransdell"
        },
        {
            "name": "Mike Williams"
        },
        {
            "name": "Nathanael Anderson"
        },
        {
            "name": "Patrick Mooney"
        },
        {
            "name": "Paul Bouzakis"
        },
        {
            "name": "Pedro Palazón"
        },
        {
            "name": "Richardo Stuven"
        },
        {
            "name": "Shaun Berryman"
        },
        {
            "name": "Steve Mason"
        },
        {
            "name": "Trent Mick"
        },
        {
            "name": "Yunong Xiao"
        }
    ],
    "dependencies": {
        "assert-plus": "^0.1.5",
        "backoff": "^2.4.0",
        "bunyan": "^1.4.0",
        "csv": "^0.4.0",
        "dtrace-provider": "^0.6.0",
        "escape-regexp-component": "^1.0.2",
        "formidable": "^1.0.14",
        "http-signature": "^0.11.0",
        "keep-alive-agent": "^0.0.1",
        "lru-cache": "^4.0.1",
        "mime": "^1.2.11",
        "negotiator": "^0.6.1",
        "node-uuid": "^1.4.1",
        "once": "^1.3.0",
        "qs": "^6.2.1",
        "semver": "^4.3.3",
        "spdy": "^3.3.3",
        "tunnel-agent": "^0.4.0",
        "vasync": "1.6.3",
        "verror": "^1.4.0"
    },
    "description": "REST framework",
    "devDependencies": {
        "cover": "^0.2.9",
        "eslint": "^0.24.0",
        "filed": "^0.1.0",
        "jscs": "^1.13.1",
        "json": "^9.0.4",
        "nodeunit": "^0.9.0",
        "watershed": "^0.3.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "03b67960d1d42a6dafcde3bd82fb882173a27678",
        "tarball": "https://registry.npmjs.org/restify/-/restify-4.3.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "93fd622b8887cb7d3f3636916c8ea6718777289b",
    "homepage": "http://restifyjs.com",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "donutespresso",
            "email": "donutespresso@gmail.com"
        },
        {
            "name": "gergelyke",
            "email": "mail@nemethgergely.com"
        },
        {
            "name": "mcavage",
            "email": "mcavage@gmail.com"
        },
        {
            "name": "micahr",
            "email": "mjr578@gmail.com"
        },
        {
            "name": "pfmooney",
            "email": "patrick.f.mooney@gmail.com"
        },
        {
            "name": "yunong",
            "email": "yjxiao@gmail.com"
        }
    ],
    "name": "restify",
    "optionalDependencies": {
        "dtrace-provider": "^0.6.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/restify/node-restify.git"
    },
    "scripts": {
        "test": "make prepush"
    },
    "version": "4.3.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module restify](#apidoc.module.restify)
1.  [function <span class="apidocSignatureSpan">restify.</span>BadDigestError (cause, message)](#apidoc.element.restify.BadDigestError)
1.  [function <span class="apidocSignatureSpan">restify.</span>BadGatewayError (cause, message)](#apidoc.element.restify.BadGatewayError)
1.  [function <span class="apidocSignatureSpan">restify.</span>BadMethodError (cause, message)](#apidoc.element.restify.BadMethodError)
1.  [function <span class="apidocSignatureSpan">restify.</span>BadRequestError (cause, message)](#apidoc.element.restify.BadRequestError)
1.  [function <span class="apidocSignatureSpan">restify.</span>BandwidthLimitExceededError (cause, message)](#apidoc.element.restify.BandwidthLimitExceededError)
1.  [function <span class="apidocSignatureSpan">restify.</span>CORS (opts)](#apidoc.element.restify.CORS)
1.  [function <span class="apidocSignatureSpan">restify.</span>ConflictError (cause, message)](#apidoc.element.restify.ConflictError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ExpectationFailedError (cause, message)](#apidoc.element.restify.ExpectationFailedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>FailedDependencyError (cause, message)](#apidoc.element.restify.FailedDependencyError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ForbiddenError (cause, message)](#apidoc.element.restify.ForbiddenError)
1.  [function <span class="apidocSignatureSpan">restify.</span>GatewayTimeoutError (cause, message)](#apidoc.element.restify.GatewayTimeoutError)
1.  [function <span class="apidocSignatureSpan">restify.</span>GoneError (cause, message)](#apidoc.element.restify.GoneError)
1.  [function <span class="apidocSignatureSpan">restify.</span>HttpClient (options)](#apidoc.element.restify.HttpClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>HttpError (options)](#apidoc.element.restify.HttpError)
1.  [function <span class="apidocSignatureSpan">restify.</span>HttpError.super_ ()](#apidoc.element.restify.HttpError.super_)
1.  [function <span class="apidocSignatureSpan">restify.</span>HttpVersionNotSupportedError (cause, message)](#apidoc.element.restify.HttpVersionNotSupportedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ImATeapotError (cause, message)](#apidoc.element.restify.ImATeapotError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InsufficientStorageError (cause, message)](#apidoc.element.restify.InsufficientStorageError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InternalError (cause, message)](#apidoc.element.restify.InternalError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InternalServerError (cause, message)](#apidoc.element.restify.InternalServerError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InvalidArgumentError (cause, message)](#apidoc.element.restify.InvalidArgumentError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InvalidContentError (cause, message)](#apidoc.element.restify.InvalidContentError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InvalidCredentialsError (cause, message)](#apidoc.element.restify.InvalidCredentialsError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InvalidHeaderError (cause, message)](#apidoc.element.restify.InvalidHeaderError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InvalidVersionError (cause, message)](#apidoc.element.restify.InvalidVersionError)
1.  [function <span class="apidocSignatureSpan">restify.</span>JsonClient (options)](#apidoc.element.restify.JsonClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>LengthRequiredError (cause, message)](#apidoc.element.restify.LengthRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>LockedError (cause, message)](#apidoc.element.restify.LockedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>LoopDetectedError (cause, message)](#apidoc.element.restify.LoopDetectedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>MethodNotAllowedError (cause, message)](#apidoc.element.restify.MethodNotAllowedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>MisdirectedRequestError (cause, message)](#apidoc.element.restify.MisdirectedRequestError)
1.  [function <span class="apidocSignatureSpan">restify.</span>MissingParameterError (cause, message)](#apidoc.element.restify.MissingParameterError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NetworkAuthenticationRequiredError (cause, message)](#apidoc.element.restify.NetworkAuthenticationRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NotAcceptableError (cause, message)](#apidoc.element.restify.NotAcceptableError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NotAuthorizedError (cause, message)](#apidoc.element.restify.NotAuthorizedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NotExtendedError (cause, message)](#apidoc.element.restify.NotExtendedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NotFoundError (cause, message)](#apidoc.element.restify.NotFoundError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NotImplementedError (cause, message)](#apidoc.element.restify.NotImplementedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>PayloadTooLargeError (cause, message)](#apidoc.element.restify.PayloadTooLargeError)
1.  [function <span class="apidocSignatureSpan">restify.</span>PaymentRequiredError (cause, message)](#apidoc.element.restify.PaymentRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>PreconditionFailedError (cause, message)](#apidoc.element.restify.PreconditionFailedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>PreconditionRequiredError (cause, message)](#apidoc.element.restify.PreconditionRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ProxyAuthenticationRequiredError (cause, message)](#apidoc.element.restify.ProxyAuthenticationRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RangeNotSatisfiableError (cause, message)](#apidoc.element.restify.RangeNotSatisfiableError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RequestExpiredError (cause, message)](#apidoc.element.restify.RequestExpiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RequestHeaderFieldsTooLargeError (cause, message)](#apidoc.element.restify.RequestHeaderFieldsTooLargeError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RequestThrottledError (cause, message)](#apidoc.element.restify.RequestThrottledError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RequestTimeoutError (cause, message)](#apidoc.element.restify.RequestTimeoutError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ResourceNotFoundError (cause, message)](#apidoc.element.restify.ResourceNotFoundError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RestError (options)](#apidoc.element.restify.RestError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ServiceUnavailableError (cause, message)](#apidoc.element.restify.ServiceUnavailableError)
1.  [function <span class="apidocSignatureSpan">restify.</span>StringClient (options)](#apidoc.element.restify.StringClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>TooManyRequestsError (cause, message)](#apidoc.element.restify.TooManyRequestsError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UnauthorizedError (cause, message)](#apidoc.element.restify.UnauthorizedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UnavailableForLegalReasonsError (cause, message)](#apidoc.element.restify.UnavailableForLegalReasonsError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UnorderedCollectionError (cause, message)](#apidoc.element.restify.UnorderedCollectionError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UnprocessableEntityError (cause, message)](#apidoc.element.restify.UnprocessableEntityError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UnsupportedMediaTypeError (cause, message)](#apidoc.element.restify.UnsupportedMediaTypeError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UpgradeRequiredError (cause, message)](#apidoc.element.restify.UpgradeRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UriTooLongError (cause, message)](#apidoc.element.restify.UriTooLongError)
1.  [function <span class="apidocSignatureSpan">restify.</span>VariantAlsoNegotiatesError (cause, message)](#apidoc.element.restify.VariantAlsoNegotiatesError)
1.  [function <span class="apidocSignatureSpan">restify.</span>WrongAcceptError (cause, message)](#apidoc.element.restify.WrongAcceptError)
1.  [function <span class="apidocSignatureSpan">restify.</span>acceptParser (acceptable)](#apidoc.element.restify.acceptParser)
1.  [function <span class="apidocSignatureSpan">restify.</span>auditLogger (options)](#apidoc.element.restify.auditLogger)
1.  [function <span class="apidocSignatureSpan">restify.</span>authorizationParser (options)](#apidoc.element.restify.authorizationParser)
1.  [function <span class="apidocSignatureSpan">restify.</span>bodyParser (options)](#apidoc.element.restify.bodyParser)
1.  [function <span class="apidocSignatureSpan">restify.</span>bunyan.RequestCaptureStream (opts)](#apidoc.element.restify.bunyan.RequestCaptureStream)
1.  [function <span class="apidocSignatureSpan">restify.</span>codeToHttpError (code, message, body)](#apidoc.element.restify.codeToHttpError)
1.  [function <span class="apidocSignatureSpan">restify.</span>conditionalRequest ()](#apidoc.element.restify.conditionalRequest)
1.  [function <span class="apidocSignatureSpan">restify.</span>createClient (options)](#apidoc.element.restify.createClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>createHttpClient (options)](#apidoc.element.restify.createHttpClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>createJSONClient (options)](#apidoc.element.restify.createJSONClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>createJsonClient (options)](#apidoc.element.restify.createJsonClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>createServer (options)](#apidoc.element.restify.createServer)
1.  [function <span class="apidocSignatureSpan">restify.</span>createStringClient (options)](#apidoc.element.restify.createStringClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>dateParser (clockSkew)](#apidoc.element.restify.dateParser)
1.  [function <span class="apidocSignatureSpan">restify.</span>fullResponse ()](#apidoc.element.restify.fullResponse)
1.  [function <span class="apidocSignatureSpan">restify.</span>gzipResponse (opts)](#apidoc.element.restify.gzipResponse)
1.  [function <span class="apidocSignatureSpan">restify.</span>httpDate (now)](#apidoc.element.restify.httpDate)
1.  [function <span class="apidocSignatureSpan">restify.</span>jsonBodyParser (options)](#apidoc.element.restify.jsonBodyParser)
1.  [function <span class="apidocSignatureSpan">restify.</span>jsonp ()](#apidoc.element.restify.jsonp)
1.  [function <span class="apidocSignatureSpan">restify.</span>multipartBodyParser (options)](#apidoc.element.restify.multipartBodyParser)
1.  [function <span class="apidocSignatureSpan">restify.</span>queryParser (options)](#apidoc.element.restify.queryParser)
1.  [function <span class="apidocSignatureSpan">restify.</span>realizeUrl (pattern, params)](#apidoc.element.restify.realizeUrl)
1.  [function <span class="apidocSignatureSpan">restify.</span>requestExpiry (options)](#apidoc.element.restify.requestExpiry)
1.  [function <span class="apidocSignatureSpan">restify.</span>requestLogger (options)](#apidoc.element.restify.requestLogger)
1.  [function <span class="apidocSignatureSpan">restify.</span>router (options)](#apidoc.element.restify.router)
1.  [function <span class="apidocSignatureSpan">restify.</span>sanitizePath (options)](#apidoc.element.restify.sanitizePath)
1.  [function <span class="apidocSignatureSpan">restify.</span>serveStatic (opts)](#apidoc.element.restify.serveStatic)
1.  [function <span class="apidocSignatureSpan">restify.</span>server (options)](#apidoc.element.restify.server)
1.  [function <span class="apidocSignatureSpan">restify.</span>throttle (options)](#apidoc.element.restify.throttle)
1.  [function <span class="apidocSignatureSpan">restify.</span>urlEncodedBodyParser (options)](#apidoc.element.restify.urlEncodedBodyParser)
1.  object <span class="apidocSignatureSpan">restify.</span>HttpClient.prototype
1.  object <span class="apidocSignatureSpan">restify.</span>HttpError.super_.prototype
1.  object <span class="apidocSignatureSpan">restify.</span>HttpError.super_.super_.prototype
1.  object <span class="apidocSignatureSpan">restify.</span>JsonClient.prototype
1.  object <span class="apidocSignatureSpan">restify.</span>StringClient.prototype
1.  object <span class="apidocSignatureSpan">restify.</span>bunyan
1.  object <span class="apidocSignatureSpan">restify.</span>bunyan.RequestCaptureStream.prototype
1.  object <span class="apidocSignatureSpan">restify.</span>bunyan.serializers
1.  object <span class="apidocSignatureSpan">restify.</span>clients
1.  object <span class="apidocSignatureSpan">restify.</span>dtrace
1.  object <span class="apidocSignatureSpan">restify.</span>errors
1.  object <span class="apidocSignatureSpan">restify.</span>formatters
1.  object <span class="apidocSignatureSpan">restify.</span>plugins
1.  object <span class="apidocSignatureSpan">restify.</span>pre
1.  object <span class="apidocSignatureSpan">restify.</span>router.prototype
1.  object <span class="apidocSignatureSpan">restify.</span>server.prototype
1.  object <span class="apidocSignatureSpan">restify.</span>upgrade
1.  object <span class="apidocSignatureSpan">restify.</span>utils

#### [module restify.BadDigestError](#apidoc.module.restify.BadDigestError)
1.  [function <span class="apidocSignatureSpan">restify.</span>BadDigestError (cause, message)](#apidoc.element.restify.BadDigestError.BadDigestError)
1.  [function <span class="apidocSignatureSpan">restify.BadDigestError.</span>super_ (options)](#apidoc.element.restify.BadDigestError.super_)
1.  string <span class="apidocSignatureSpan">restify.BadDigestError.</span>displayName

#### [module restify.BadGatewayError](#apidoc.module.restify.BadGatewayError)
1.  [function <span class="apidocSignatureSpan">restify.</span>BadGatewayError (cause, message)](#apidoc.element.restify.BadGatewayError.BadGatewayError)
1.  [function <span class="apidocSignatureSpan">restify.BadGatewayError.</span>super_ (options)](#apidoc.element.restify.BadGatewayError.super_)
1.  string <span class="apidocSignatureSpan">restify.BadGatewayError.</span>displayName

#### [module restify.BadMethodError](#apidoc.module.restify.BadMethodError)
1.  [function <span class="apidocSignatureSpan">restify.</span>BadMethodError (cause, message)](#apidoc.element.restify.BadMethodError.BadMethodError)
1.  [function <span class="apidocSignatureSpan">restify.BadMethodError.</span>super_ (options)](#apidoc.element.restify.BadMethodError.super_)
1.  string <span class="apidocSignatureSpan">restify.BadMethodError.</span>displayName

#### [module restify.BadRequestError](#apidoc.module.restify.BadRequestError)
1.  [function <span class="apidocSignatureSpan">restify.</span>BadRequestError (cause, message)](#apidoc.element.restify.BadRequestError.BadRequestError)
1.  [function <span class="apidocSignatureSpan">restify.BadRequestError.</span>super_ (options)](#apidoc.element.restify.BadRequestError.super_)
1.  string <span class="apidocSignatureSpan">restify.BadRequestError.</span>displayName

#### [module restify.BandwidthLimitExceededError](#apidoc.module.restify.BandwidthLimitExceededError)
1.  [function <span class="apidocSignatureSpan">restify.</span>BandwidthLimitExceededError (cause, message)](#apidoc.element.restify.BandwidthLimitExceededError.BandwidthLimitExceededError)
1.  [function <span class="apidocSignatureSpan">restify.BandwidthLimitExceededError.</span>super_ (options)](#apidoc.element.restify.BandwidthLimitExceededError.super_)
1.  string <span class="apidocSignatureSpan">restify.BandwidthLimitExceededError.</span>displayName

#### [module restify.CORS](#apidoc.module.restify.CORS)
1.  boolean <span class="apidocSignatureSpan">restify.CORS.</span>credentials
1.  [function <span class="apidocSignatureSpan">restify.</span>CORS (opts)](#apidoc.element.restify.CORS.CORS)
1.  [function <span class="apidocSignatureSpan">restify.CORS.</span>matchOrigin (req, origins)](#apidoc.element.restify.CORS.matchOrigin)
1.  object <span class="apidocSignatureSpan">restify.CORS.</span>ALLOW_HEADERS
1.  object <span class="apidocSignatureSpan">restify.CORS.</span>EXPOSE_HEADERS
1.  object <span class="apidocSignatureSpan">restify.CORS.</span>origins

#### [module restify.ConflictError](#apidoc.module.restify.ConflictError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ConflictError (cause, message)](#apidoc.element.restify.ConflictError.ConflictError)
1.  [function <span class="apidocSignatureSpan">restify.ConflictError.</span>super_ (options)](#apidoc.element.restify.ConflictError.super_)
1.  string <span class="apidocSignatureSpan">restify.ConflictError.</span>displayName

#### [module restify.ExpectationFailedError](#apidoc.module.restify.ExpectationFailedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ExpectationFailedError (cause, message)](#apidoc.element.restify.ExpectationFailedError.ExpectationFailedError)
1.  [function <span class="apidocSignatureSpan">restify.ExpectationFailedError.</span>super_ (options)](#apidoc.element.restify.ExpectationFailedError.super_)
1.  string <span class="apidocSignatureSpan">restify.ExpectationFailedError.</span>displayName

#### [module restify.FailedDependencyError](#apidoc.module.restify.FailedDependencyError)
1.  [function <span class="apidocSignatureSpan">restify.</span>FailedDependencyError (cause, message)](#apidoc.element.restify.FailedDependencyError.FailedDependencyError)
1.  [function <span class="apidocSignatureSpan">restify.FailedDependencyError.</span>super_ (options)](#apidoc.element.restify.FailedDependencyError.super_)
1.  string <span class="apidocSignatureSpan">restify.FailedDependencyError.</span>displayName

#### [module restify.ForbiddenError](#apidoc.module.restify.ForbiddenError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ForbiddenError (cause, message)](#apidoc.element.restify.ForbiddenError.ForbiddenError)
1.  [function <span class="apidocSignatureSpan">restify.ForbiddenError.</span>super_ (options)](#apidoc.element.restify.ForbiddenError.super_)
1.  string <span class="apidocSignatureSpan">restify.ForbiddenError.</span>displayName

#### [module restify.GatewayTimeoutError](#apidoc.module.restify.GatewayTimeoutError)
1.  [function <span class="apidocSignatureSpan">restify.</span>GatewayTimeoutError (cause, message)](#apidoc.element.restify.GatewayTimeoutError.GatewayTimeoutError)
1.  [function <span class="apidocSignatureSpan">restify.GatewayTimeoutError.</span>super_ (options)](#apidoc.element.restify.GatewayTimeoutError.super_)
1.  string <span class="apidocSignatureSpan">restify.GatewayTimeoutError.</span>displayName

#### [module restify.GoneError](#apidoc.module.restify.GoneError)
1.  [function <span class="apidocSignatureSpan">restify.</span>GoneError (cause, message)](#apidoc.element.restify.GoneError.GoneError)
1.  [function <span class="apidocSignatureSpan">restify.GoneError.</span>super_ (options)](#apidoc.element.restify.GoneError.super_)
1.  string <span class="apidocSignatureSpan">restify.GoneError.</span>displayName

#### [module restify.HttpClient](#apidoc.module.restify.HttpClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>HttpClient (options)](#apidoc.element.restify.HttpClient.HttpClient)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.</span>super_ ()](#apidoc.element.restify.HttpClient.super_)

#### [module restify.HttpClient.prototype](#apidoc.module.restify.HttpClient.prototype)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>_options (method, options)](#apidoc.element.restify.HttpClient.prototype._options)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>basicAuth (username, password)](#apidoc.element.restify.HttpClient.prototype.basicAuth)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>close ()](#apidoc.element.restify.HttpClient.prototype.close)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>del (options, callback)](#apidoc.element.restify.HttpClient.prototype.del)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>get (options, callback)](#apidoc.element.restify.HttpClient.prototype.get)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>head (options, callback)](#apidoc.element.restify.HttpClient.prototype.head)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>opts (options, callback)](#apidoc.element.restify.HttpClient.prototype.opts)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>patch (options, callback)](#apidoc.element.restify.HttpClient.prototype.patch)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>post (options, callback)](#apidoc.element.restify.HttpClient.prototype.post)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>put (options, callback)](#apidoc.element.restify.HttpClient.prototype.put)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>read (options, callback)](#apidoc.element.restify.HttpClient.prototype.read)
1.  [function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>request (opts, cb)](#apidoc.element.restify.HttpClient.prototype.request)

#### [module restify.HttpError](#apidoc.module.restify.HttpError)
1.  [function <span class="apidocSignatureSpan">restify.</span>HttpError (options)](#apidoc.element.restify.HttpError.HttpError)
1.  [function <span class="apidocSignatureSpan">restify.HttpError.</span>super_ ()](#apidoc.element.restify.HttpError.super_)

#### [module restify.HttpError.super_](#apidoc.module.restify.HttpError.super_)
1.  [function <span class="apidocSignatureSpan">restify.HttpError.</span>super_ ()](#apidoc.element.restify.HttpError.super_.super_)

#### [module restify.HttpError.super_.prototype](#apidoc.module.restify.HttpError.super_.prototype)
1.  [function <span class="apidocSignatureSpan">restify.HttpError.super_.prototype.</span>cause (c)](#apidoc.element.restify.HttpError.super_.prototype.cause)
1.  [function <span class="apidocSignatureSpan">restify.HttpError.super_.prototype.</span>toString ()](#apidoc.element.restify.HttpError.super_.prototype.toString)
1.  string <span class="apidocSignatureSpan">restify.HttpError.super_.prototype.</span>name

#### [module restify.HttpError.super_.super_.prototype](#apidoc.module.restify.HttpError.super_.super_.prototype)
1.  [function <span class="apidocSignatureSpan">restify.HttpError.super_.super_.prototype.</span>cause ()](#apidoc.element.restify.HttpError.super_.super_.prototype.cause)
1.  [function <span class="apidocSignatureSpan">restify.HttpError.super_.super_.prototype.</span>toString ()](#apidoc.element.restify.HttpError.super_.super_.prototype.toString)
1.  string <span class="apidocSignatureSpan">restify.HttpError.super_.super_.prototype.</span>name

#### [module restify.HttpVersionNotSupportedError](#apidoc.module.restify.HttpVersionNotSupportedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>HttpVersionNotSupportedError (cause, message)](#apidoc.element.restify.HttpVersionNotSupportedError.HttpVersionNotSupportedError)
1.  [function <span class="apidocSignatureSpan">restify.HttpVersionNotSupportedError.</span>super_ (options)](#apidoc.element.restify.HttpVersionNotSupportedError.super_)
1.  string <span class="apidocSignatureSpan">restify.HttpVersionNotSupportedError.</span>displayName

#### [module restify.ImATeapotError](#apidoc.module.restify.ImATeapotError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ImATeapotError (cause, message)](#apidoc.element.restify.ImATeapotError.ImATeapotError)
1.  [function <span class="apidocSignatureSpan">restify.ImATeapotError.</span>super_ (options)](#apidoc.element.restify.ImATeapotError.super_)
1.  string <span class="apidocSignatureSpan">restify.ImATeapotError.</span>displayName

#### [module restify.InsufficientStorageError](#apidoc.module.restify.InsufficientStorageError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InsufficientStorageError (cause, message)](#apidoc.element.restify.InsufficientStorageError.InsufficientStorageError)
1.  [function <span class="apidocSignatureSpan">restify.InsufficientStorageError.</span>super_ (options)](#apidoc.element.restify.InsufficientStorageError.super_)
1.  string <span class="apidocSignatureSpan">restify.InsufficientStorageError.</span>displayName

#### [module restify.InternalError](#apidoc.module.restify.InternalError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InternalError (cause, message)](#apidoc.element.restify.InternalError.InternalError)
1.  [function <span class="apidocSignatureSpan">restify.InternalError.</span>super_ (options)](#apidoc.element.restify.InternalError.super_)
1.  string <span class="apidocSignatureSpan">restify.InternalError.</span>displayName

#### [module restify.InternalServerError](#apidoc.module.restify.InternalServerError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InternalServerError (cause, message)](#apidoc.element.restify.InternalServerError.InternalServerError)
1.  [function <span class="apidocSignatureSpan">restify.InternalServerError.</span>super_ (options)](#apidoc.element.restify.InternalServerError.super_)
1.  string <span class="apidocSignatureSpan">restify.InternalServerError.</span>displayName

#### [module restify.InvalidArgumentError](#apidoc.module.restify.InvalidArgumentError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InvalidArgumentError (cause, message)](#apidoc.element.restify.InvalidArgumentError.InvalidArgumentError)
1.  [function <span class="apidocSignatureSpan">restify.InvalidArgumentError.</span>super_ (options)](#apidoc.element.restify.InvalidArgumentError.super_)
1.  string <span class="apidocSignatureSpan">restify.InvalidArgumentError.</span>displayName

#### [module restify.InvalidContentError](#apidoc.module.restify.InvalidContentError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InvalidContentError (cause, message)](#apidoc.element.restify.InvalidContentError.InvalidContentError)
1.  [function <span class="apidocSignatureSpan">restify.InvalidContentError.</span>super_ (options)](#apidoc.element.restify.InvalidContentError.super_)
1.  string <span class="apidocSignatureSpan">restify.InvalidContentError.</span>displayName

#### [module restify.InvalidCredentialsError](#apidoc.module.restify.InvalidCredentialsError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InvalidCredentialsError (cause, message)](#apidoc.element.restify.InvalidCredentialsError.InvalidCredentialsError)
1.  [function <span class="apidocSignatureSpan">restify.InvalidCredentialsError.</span>super_ (options)](#apidoc.element.restify.InvalidCredentialsError.super_)
1.  string <span class="apidocSignatureSpan">restify.InvalidCredentialsError.</span>displayName

#### [module restify.InvalidHeaderError](#apidoc.module.restify.InvalidHeaderError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InvalidHeaderError (cause, message)](#apidoc.element.restify.InvalidHeaderError.InvalidHeaderError)
1.  [function <span class="apidocSignatureSpan">restify.InvalidHeaderError.</span>super_ (options)](#apidoc.element.restify.InvalidHeaderError.super_)
1.  string <span class="apidocSignatureSpan">restify.InvalidHeaderError.</span>displayName

#### [module restify.InvalidVersionError](#apidoc.module.restify.InvalidVersionError)
1.  [function <span class="apidocSignatureSpan">restify.</span>InvalidVersionError (cause, message)](#apidoc.element.restify.InvalidVersionError.InvalidVersionError)
1.  [function <span class="apidocSignatureSpan">restify.InvalidVersionError.</span>super_ (options)](#apidoc.element.restify.InvalidVersionError.super_)
1.  string <span class="apidocSignatureSpan">restify.InvalidVersionError.</span>displayName

#### [module restify.JsonClient](#apidoc.module.restify.JsonClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>JsonClient (options)](#apidoc.element.restify.JsonClient.JsonClient)
1.  [function <span class="apidocSignatureSpan">restify.JsonClient.</span>super_ (options)](#apidoc.element.restify.JsonClient.super_)

#### [module restify.JsonClient.prototype](#apidoc.module.restify.JsonClient.prototype)
1.  [function <span class="apidocSignatureSpan">restify.JsonClient.prototype.</span>parse (req, callback)](#apidoc.element.restify.JsonClient.prototype.parse)
1.  [function <span class="apidocSignatureSpan">restify.JsonClient.prototype.</span>write (options, body, callback)](#apidoc.element.restify.JsonClient.prototype.write)

#### [module restify.LengthRequiredError](#apidoc.module.restify.LengthRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>LengthRequiredError (cause, message)](#apidoc.element.restify.LengthRequiredError.LengthRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.LengthRequiredError.</span>super_ (options)](#apidoc.element.restify.LengthRequiredError.super_)
1.  string <span class="apidocSignatureSpan">restify.LengthRequiredError.</span>displayName

#### [module restify.LockedError](#apidoc.module.restify.LockedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>LockedError (cause, message)](#apidoc.element.restify.LockedError.LockedError)
1.  [function <span class="apidocSignatureSpan">restify.LockedError.</span>super_ (options)](#apidoc.element.restify.LockedError.super_)
1.  string <span class="apidocSignatureSpan">restify.LockedError.</span>displayName

#### [module restify.LoopDetectedError](#apidoc.module.restify.LoopDetectedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>LoopDetectedError (cause, message)](#apidoc.element.restify.LoopDetectedError.LoopDetectedError)
1.  [function <span class="apidocSignatureSpan">restify.LoopDetectedError.</span>super_ (options)](#apidoc.element.restify.LoopDetectedError.super_)
1.  string <span class="apidocSignatureSpan">restify.LoopDetectedError.</span>displayName

#### [module restify.MethodNotAllowedError](#apidoc.module.restify.MethodNotAllowedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>MethodNotAllowedError (cause, message)](#apidoc.element.restify.MethodNotAllowedError.MethodNotAllowedError)
1.  [function <span class="apidocSignatureSpan">restify.MethodNotAllowedError.</span>super_ (options)](#apidoc.element.restify.MethodNotAllowedError.super_)
1.  string <span class="apidocSignatureSpan">restify.MethodNotAllowedError.</span>displayName

#### [module restify.MisdirectedRequestError](#apidoc.module.restify.MisdirectedRequestError)
1.  [function <span class="apidocSignatureSpan">restify.</span>MisdirectedRequestError (cause, message)](#apidoc.element.restify.MisdirectedRequestError.MisdirectedRequestError)
1.  [function <span class="apidocSignatureSpan">restify.MisdirectedRequestError.</span>super_ (options)](#apidoc.element.restify.MisdirectedRequestError.super_)
1.  string <span class="apidocSignatureSpan">restify.MisdirectedRequestError.</span>displayName

#### [module restify.MissingParameterError](#apidoc.module.restify.MissingParameterError)
1.  [function <span class="apidocSignatureSpan">restify.</span>MissingParameterError (cause, message)](#apidoc.element.restify.MissingParameterError.MissingParameterError)
1.  [function <span class="apidocSignatureSpan">restify.MissingParameterError.</span>super_ (options)](#apidoc.element.restify.MissingParameterError.super_)
1.  string <span class="apidocSignatureSpan">restify.MissingParameterError.</span>displayName

#### [module restify.NetworkAuthenticationRequiredError](#apidoc.module.restify.NetworkAuthenticationRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NetworkAuthenticationRequiredError (cause, message)](#apidoc.element.restify.NetworkAuthenticationRequiredError.NetworkAuthenticationRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.NetworkAuthenticationRequiredError.</span>super_ (options)](#apidoc.element.restify.NetworkAuthenticationRequiredError.super_)
1.  string <span class="apidocSignatureSpan">restify.NetworkAuthenticationRequiredError.</span>displayName

#### [module restify.NotAcceptableError](#apidoc.module.restify.NotAcceptableError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NotAcceptableError (cause, message)](#apidoc.element.restify.NotAcceptableError.NotAcceptableError)
1.  [function <span class="apidocSignatureSpan">restify.NotAcceptableError.</span>super_ (options)](#apidoc.element.restify.NotAcceptableError.super_)
1.  string <span class="apidocSignatureSpan">restify.NotAcceptableError.</span>displayName

#### [module restify.NotAuthorizedError](#apidoc.module.restify.NotAuthorizedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NotAuthorizedError (cause, message)](#apidoc.element.restify.NotAuthorizedError.NotAuthorizedError)
1.  [function <span class="apidocSignatureSpan">restify.NotAuthorizedError.</span>super_ (options)](#apidoc.element.restify.NotAuthorizedError.super_)
1.  string <span class="apidocSignatureSpan">restify.NotAuthorizedError.</span>displayName

#### [module restify.NotExtendedError](#apidoc.module.restify.NotExtendedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NotExtendedError (cause, message)](#apidoc.element.restify.NotExtendedError.NotExtendedError)
1.  [function <span class="apidocSignatureSpan">restify.NotExtendedError.</span>super_ (options)](#apidoc.element.restify.NotExtendedError.super_)
1.  string <span class="apidocSignatureSpan">restify.NotExtendedError.</span>displayName

#### [module restify.NotFoundError](#apidoc.module.restify.NotFoundError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NotFoundError (cause, message)](#apidoc.element.restify.NotFoundError.NotFoundError)
1.  [function <span class="apidocSignatureSpan">restify.NotFoundError.</span>super_ (options)](#apidoc.element.restify.NotFoundError.super_)
1.  string <span class="apidocSignatureSpan">restify.NotFoundError.</span>displayName

#### [module restify.NotImplementedError](#apidoc.module.restify.NotImplementedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>NotImplementedError (cause, message)](#apidoc.element.restify.NotImplementedError.NotImplementedError)
1.  [function <span class="apidocSignatureSpan">restify.NotImplementedError.</span>super_ (options)](#apidoc.element.restify.NotImplementedError.super_)
1.  string <span class="apidocSignatureSpan">restify.NotImplementedError.</span>displayName

#### [module restify.PayloadTooLargeError](#apidoc.module.restify.PayloadTooLargeError)
1.  [function <span class="apidocSignatureSpan">restify.</span>PayloadTooLargeError (cause, message)](#apidoc.element.restify.PayloadTooLargeError.PayloadTooLargeError)
1.  [function <span class="apidocSignatureSpan">restify.PayloadTooLargeError.</span>super_ (options)](#apidoc.element.restify.PayloadTooLargeError.super_)
1.  string <span class="apidocSignatureSpan">restify.PayloadTooLargeError.</span>displayName

#### [module restify.PaymentRequiredError](#apidoc.module.restify.PaymentRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>PaymentRequiredError (cause, message)](#apidoc.element.restify.PaymentRequiredError.PaymentRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.PaymentRequiredError.</span>super_ (options)](#apidoc.element.restify.PaymentRequiredError.super_)
1.  string <span class="apidocSignatureSpan">restify.PaymentRequiredError.</span>displayName

#### [module restify.PreconditionFailedError](#apidoc.module.restify.PreconditionFailedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>PreconditionFailedError (cause, message)](#apidoc.element.restify.PreconditionFailedError.PreconditionFailedError)
1.  [function <span class="apidocSignatureSpan">restify.PreconditionFailedError.</span>super_ (options)](#apidoc.element.restify.PreconditionFailedError.super_)
1.  string <span class="apidocSignatureSpan">restify.PreconditionFailedError.</span>displayName

#### [module restify.PreconditionRequiredError](#apidoc.module.restify.PreconditionRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>PreconditionRequiredError (cause, message)](#apidoc.element.restify.PreconditionRequiredError.PreconditionRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.PreconditionRequiredError.</span>super_ (options)](#apidoc.element.restify.PreconditionRequiredError.super_)
1.  string <span class="apidocSignatureSpan">restify.PreconditionRequiredError.</span>displayName

#### [module restify.ProxyAuthenticationRequiredError](#apidoc.module.restify.ProxyAuthenticationRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ProxyAuthenticationRequiredError (cause, message)](#apidoc.element.restify.ProxyAuthenticationRequiredError.ProxyAuthenticationRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.ProxyAuthenticationRequiredError.</span>super_ (options)](#apidoc.element.restify.ProxyAuthenticationRequiredError.super_)
1.  string <span class="apidocSignatureSpan">restify.ProxyAuthenticationRequiredError.</span>displayName

#### [module restify.RangeNotSatisfiableError](#apidoc.module.restify.RangeNotSatisfiableError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RangeNotSatisfiableError (cause, message)](#apidoc.element.restify.RangeNotSatisfiableError.RangeNotSatisfiableError)
1.  [function <span class="apidocSignatureSpan">restify.RangeNotSatisfiableError.</span>super_ (options)](#apidoc.element.restify.RangeNotSatisfiableError.super_)
1.  string <span class="apidocSignatureSpan">restify.RangeNotSatisfiableError.</span>displayName

#### [module restify.RequestExpiredError](#apidoc.module.restify.RequestExpiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RequestExpiredError (cause, message)](#apidoc.element.restify.RequestExpiredError.RequestExpiredError)
1.  [function <span class="apidocSignatureSpan">restify.RequestExpiredError.</span>super_ (options)](#apidoc.element.restify.RequestExpiredError.super_)
1.  string <span class="apidocSignatureSpan">restify.RequestExpiredError.</span>displayName

#### [module restify.RequestHeaderFieldsTooLargeError](#apidoc.module.restify.RequestHeaderFieldsTooLargeError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RequestHeaderFieldsTooLargeError (cause, message)](#apidoc.element.restify.RequestHeaderFieldsTooLargeError.RequestHeaderFieldsTooLargeError)
1.  [function <span class="apidocSignatureSpan">restify.RequestHeaderFieldsTooLargeError.</span>super_ (options)](#apidoc.element.restify.RequestHeaderFieldsTooLargeError.super_)
1.  string <span class="apidocSignatureSpan">restify.RequestHeaderFieldsTooLargeError.</span>displayName

#### [module restify.RequestThrottledError](#apidoc.module.restify.RequestThrottledError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RequestThrottledError (cause, message)](#apidoc.element.restify.RequestThrottledError.RequestThrottledError)
1.  [function <span class="apidocSignatureSpan">restify.RequestThrottledError.</span>super_ (options)](#apidoc.element.restify.RequestThrottledError.super_)
1.  string <span class="apidocSignatureSpan">restify.RequestThrottledError.</span>displayName

#### [module restify.RequestTimeoutError](#apidoc.module.restify.RequestTimeoutError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RequestTimeoutError (cause, message)](#apidoc.element.restify.RequestTimeoutError.RequestTimeoutError)
1.  [function <span class="apidocSignatureSpan">restify.RequestTimeoutError.</span>super_ (options)](#apidoc.element.restify.RequestTimeoutError.super_)
1.  string <span class="apidocSignatureSpan">restify.RequestTimeoutError.</span>displayName

#### [module restify.ResourceNotFoundError](#apidoc.module.restify.ResourceNotFoundError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ResourceNotFoundError (cause, message)](#apidoc.element.restify.ResourceNotFoundError.ResourceNotFoundError)
1.  [function <span class="apidocSignatureSpan">restify.ResourceNotFoundError.</span>super_ (options)](#apidoc.element.restify.ResourceNotFoundError.super_)
1.  string <span class="apidocSignatureSpan">restify.ResourceNotFoundError.</span>displayName

#### [module restify.RestError](#apidoc.module.restify.RestError)
1.  [function <span class="apidocSignatureSpan">restify.</span>RestError (options)](#apidoc.element.restify.RestError.RestError)
1.  [function <span class="apidocSignatureSpan">restify.RestError.</span>super_ (options)](#apidoc.element.restify.RestError.super_)

#### [module restify.ServiceUnavailableError](#apidoc.module.restify.ServiceUnavailableError)
1.  [function <span class="apidocSignatureSpan">restify.</span>ServiceUnavailableError (cause, message)](#apidoc.element.restify.ServiceUnavailableError.ServiceUnavailableError)
1.  [function <span class="apidocSignatureSpan">restify.ServiceUnavailableError.</span>super_ (options)](#apidoc.element.restify.ServiceUnavailableError.super_)
1.  string <span class="apidocSignatureSpan">restify.ServiceUnavailableError.</span>displayName

#### [module restify.StringClient](#apidoc.module.restify.StringClient)
1.  [function <span class="apidocSignatureSpan">restify.</span>StringClient (options)](#apidoc.element.restify.StringClient.StringClient)
1.  [function <span class="apidocSignatureSpan">restify.StringClient.</span>super_ (options)](#apidoc.element.restify.StringClient.super_)

#### [module restify.StringClient.prototype](#apidoc.module.restify.StringClient.prototype)
1.  [function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>parse (req, callback)](#apidoc.element.restify.StringClient.prototype.parse)
1.  [function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>patch (options, body, callback)](#apidoc.element.restify.StringClient.prototype.patch)
1.  [function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>post (options, body, callback)](#apidoc.element.restify.StringClient.prototype.post)
1.  [function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>put (options, body, callback)](#apidoc.element.restify.StringClient.prototype.put)
1.  [function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>read (options, callback)](#apidoc.element.restify.StringClient.prototype.read)
1.  [function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>write (options, body, callback)](#apidoc.element.restify.StringClient.prototype.write)

#### [module restify.TooManyRequestsError](#apidoc.module.restify.TooManyRequestsError)
1.  [function <span class="apidocSignatureSpan">restify.</span>TooManyRequestsError (cause, message)](#apidoc.element.restify.TooManyRequestsError.TooManyRequestsError)
1.  [function <span class="apidocSignatureSpan">restify.TooManyRequestsError.</span>super_ (options)](#apidoc.element.restify.TooManyRequestsError.super_)
1.  string <span class="apidocSignatureSpan">restify.TooManyRequestsError.</span>displayName

#### [module restify.UnauthorizedError](#apidoc.module.restify.UnauthorizedError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UnauthorizedError (cause, message)](#apidoc.element.restify.UnauthorizedError.UnauthorizedError)
1.  [function <span class="apidocSignatureSpan">restify.UnauthorizedError.</span>super_ (options)](#apidoc.element.restify.UnauthorizedError.super_)
1.  string <span class="apidocSignatureSpan">restify.UnauthorizedError.</span>displayName

#### [module restify.UnavailableForLegalReasonsError](#apidoc.module.restify.UnavailableForLegalReasonsError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UnavailableForLegalReasonsError (cause, message)](#apidoc.element.restify.UnavailableForLegalReasonsError.UnavailableForLegalReasonsError)
1.  [function <span class="apidocSignatureSpan">restify.UnavailableForLegalReasonsError.</span>super_ (options)](#apidoc.element.restify.UnavailableForLegalReasonsError.super_)
1.  string <span class="apidocSignatureSpan">restify.UnavailableForLegalReasonsError.</span>displayName

#### [module restify.UnorderedCollectionError](#apidoc.module.restify.UnorderedCollectionError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UnorderedCollectionError (cause, message)](#apidoc.element.restify.UnorderedCollectionError.UnorderedCollectionError)
1.  [function <span class="apidocSignatureSpan">restify.UnorderedCollectionError.</span>super_ (options)](#apidoc.element.restify.UnorderedCollectionError.super_)
1.  string <span class="apidocSignatureSpan">restify.UnorderedCollectionError.</span>displayName

#### [module restify.UnprocessableEntityError](#apidoc.module.restify.UnprocessableEntityError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UnprocessableEntityError (cause, message)](#apidoc.element.restify.UnprocessableEntityError.UnprocessableEntityError)
1.  [function <span class="apidocSignatureSpan">restify.UnprocessableEntityError.</span>super_ (options)](#apidoc.element.restify.UnprocessableEntityError.super_)
1.  string <span class="apidocSignatureSpan">restify.UnprocessableEntityError.</span>displayName

#### [module restify.UnsupportedMediaTypeError](#apidoc.module.restify.UnsupportedMediaTypeError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UnsupportedMediaTypeError (cause, message)](#apidoc.element.restify.UnsupportedMediaTypeError.UnsupportedMediaTypeError)
1.  [function <span class="apidocSignatureSpan">restify.UnsupportedMediaTypeError.</span>super_ (options)](#apidoc.element.restify.UnsupportedMediaTypeError.super_)
1.  string <span class="apidocSignatureSpan">restify.UnsupportedMediaTypeError.</span>displayName

#### [module restify.UpgradeRequiredError](#apidoc.module.restify.UpgradeRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UpgradeRequiredError (cause, message)](#apidoc.element.restify.UpgradeRequiredError.UpgradeRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.UpgradeRequiredError.</span>super_ (options)](#apidoc.element.restify.UpgradeRequiredError.super_)
1.  string <span class="apidocSignatureSpan">restify.UpgradeRequiredError.</span>displayName

#### [module restify.UriTooLongError](#apidoc.module.restify.UriTooLongError)
1.  [function <span class="apidocSignatureSpan">restify.</span>UriTooLongError (cause, message)](#apidoc.element.restify.UriTooLongError.UriTooLongError)
1.  [function <span class="apidocSignatureSpan">restify.UriTooLongError.</span>super_ (options)](#apidoc.element.restify.UriTooLongError.super_)
1.  string <span class="apidocSignatureSpan">restify.UriTooLongError.</span>displayName

#### [module restify.VariantAlsoNegotiatesError](#apidoc.module.restify.VariantAlsoNegotiatesError)
1.  [function <span class="apidocSignatureSpan">restify.</span>VariantAlsoNegotiatesError (cause, message)](#apidoc.element.restify.VariantAlsoNegotiatesError.VariantAlsoNegotiatesError)
1.  [function <span class="apidocSignatureSpan">restify.VariantAlsoNegotiatesError.</span>super_ (options)](#apidoc.element.restify.VariantAlsoNegotiatesError.super_)
1.  string <span class="apidocSignatureSpan">restify.VariantAlsoNegotiatesError.</span>displayName

#### [module restify.WrongAcceptError](#apidoc.module.restify.WrongAcceptError)
1.  [function <span class="apidocSignatureSpan">restify.</span>WrongAcceptError (cause, message)](#apidoc.element.restify.WrongAcceptError.WrongAcceptError)
1.  [function <span class="apidocSignatureSpan">restify.WrongAcceptError.</span>super_ (options)](#apidoc.element.restify.WrongAcceptError.super_)
1.  string <span class="apidocSignatureSpan">restify.WrongAcceptError.</span>displayName

#### [module restify.bunyan](#apidoc.module.restify.bunyan)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.</span>RequestCaptureStream (opts)](#apidoc.element.restify.bunyan.RequestCaptureStream)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.</span>createLogger (name)](#apidoc.element.restify.bunyan.createLogger)
1.  object <span class="apidocSignatureSpan">restify.bunyan.</span>serializers

#### [module restify.bunyan.RequestCaptureStream](#apidoc.module.restify.bunyan.RequestCaptureStream)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.</span>RequestCaptureStream (opts)](#apidoc.element.restify.bunyan.RequestCaptureStream.RequestCaptureStream)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.RequestCaptureStream.</span>super_ ()](#apidoc.element.restify.bunyan.RequestCaptureStream.super_)

#### [module restify.bunyan.RequestCaptureStream.prototype](#apidoc.module.restify.bunyan.RequestCaptureStream.prototype)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.RequestCaptureStream.prototype.</span>toString ()](#apidoc.element.restify.bunyan.RequestCaptureStream.prototype.toString)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.RequestCaptureStream.prototype.</span>write (record)](#apidoc.element.restify.bunyan.RequestCaptureStream.prototype.write)

#### [module restify.bunyan.serializers](#apidoc.module.restify.bunyan.serializers)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.serializers.</span>client_req (req)](#apidoc.element.restify.bunyan.serializers.client_req)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.serializers.</span>client_res (res)](#apidoc.element.restify.bunyan.serializers.client_res)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.serializers.</span>err (err)](#apidoc.element.restify.bunyan.serializers.err)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.serializers.</span>req (req)](#apidoc.element.restify.bunyan.serializers.req)
1.  [function <span class="apidocSignatureSpan">restify.bunyan.serializers.</span>res (res)](#apidoc.element.restify.bunyan.serializers.res)

#### [module restify.clients](#apidoc.module.restify.clients)
1.  [function <span class="apidocSignatureSpan">restify.clients.</span>HttpClient (options)](#apidoc.element.restify.clients.HttpClient)
1.  [function <span class="apidocSignatureSpan">restify.clients.</span>JsonClient (options)](#apidoc.element.restify.clients.JsonClient)
1.  [function <span class="apidocSignatureSpan">restify.clients.</span>StringClient (options)](#apidoc.element.restify.clients.StringClient)

#### [module restify.dtrace](#apidoc.module.restify.dtrace)
1.  [function <span class="apidocSignatureSpan">restify.dtrace.</span>nextId ()](#apidoc.element.restify.dtrace.nextId)
1.  object <span class="apidocSignatureSpan">restify.dtrace.</span>_rstfy_probes
1.  object <span class="apidocSignatureSpan">restify.dtrace.</span>client-error
1.  object <span class="apidocSignatureSpan">restify.dtrace.</span>client-request
1.  object <span class="apidocSignatureSpan">restify.dtrace.</span>client-response
1.  object <span class="apidocSignatureSpan">restify.dtrace.</span>handler-done
1.  object <span class="apidocSignatureSpan">restify.dtrace.</span>handler-start
1.  object <span class="apidocSignatureSpan">restify.dtrace.</span>route-done
1.  object <span class="apidocSignatureSpan">restify.dtrace.</span>route-start

#### [module restify.errors](#apidoc.module.restify.errors)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>BadDigestError (cause, message)](#apidoc.element.restify.errors.BadDigestError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>BadGatewayError (cause, message)](#apidoc.element.restify.errors.BadGatewayError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>BadMethodError (cause, message)](#apidoc.element.restify.errors.BadMethodError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>BadRequestError (cause, message)](#apidoc.element.restify.errors.BadRequestError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>BandwidthLimitExceededError (cause, message)](#apidoc.element.restify.errors.BandwidthLimitExceededError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>ConflictError (cause, message)](#apidoc.element.restify.errors.ConflictError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>ExpectationFailedError (cause, message)](#apidoc.element.restify.errors.ExpectationFailedError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>FailedDependencyError (cause, message)](#apidoc.element.restify.errors.FailedDependencyError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>ForbiddenError (cause, message)](#apidoc.element.restify.errors.ForbiddenError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>GatewayTimeoutError (cause, message)](#apidoc.element.restify.errors.GatewayTimeoutError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>GoneError (cause, message)](#apidoc.element.restify.errors.GoneError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>HttpError (options)](#apidoc.element.restify.errors.HttpError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>HttpVersionNotSupportedError (cause, message)](#apidoc.element.restify.errors.HttpVersionNotSupportedError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>ImATeapotError (cause, message)](#apidoc.element.restify.errors.ImATeapotError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>InsufficientStorageError (cause, message)](#apidoc.element.restify.errors.InsufficientStorageError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>InternalError (cause, message)](#apidoc.element.restify.errors.InternalError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>InternalServerError (cause, message)](#apidoc.element.restify.errors.InternalServerError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>InvalidArgumentError (cause, message)](#apidoc.element.restify.errors.InvalidArgumentError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>InvalidContentError (cause, message)](#apidoc.element.restify.errors.InvalidContentError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>InvalidCredentialsError (cause, message)](#apidoc.element.restify.errors.InvalidCredentialsError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>InvalidHeaderError (cause, message)](#apidoc.element.restify.errors.InvalidHeaderError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>InvalidVersionError (cause, message)](#apidoc.element.restify.errors.InvalidVersionError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>LengthRequiredError (cause, message)](#apidoc.element.restify.errors.LengthRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>LockedError (cause, message)](#apidoc.element.restify.errors.LockedError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>LoopDetectedError (cause, message)](#apidoc.element.restify.errors.LoopDetectedError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>MethodNotAllowedError (cause, message)](#apidoc.element.restify.errors.MethodNotAllowedError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>MisdirectedRequestError (cause, message)](#apidoc.element.restify.errors.MisdirectedRequestError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>MissingParameterError (cause, message)](#apidoc.element.restify.errors.MissingParameterError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>NetworkAuthenticationRequiredError (cause, message)](#apidoc.element.restify.errors.NetworkAuthenticationRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>NotAcceptableError (cause, message)](#apidoc.element.restify.errors.NotAcceptableError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>NotAuthorizedError (cause, message)](#apidoc.element.restify.errors.NotAuthorizedError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>NotExtendedError (cause, message)](#apidoc.element.restify.errors.NotExtendedError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>NotFoundError (cause, message)](#apidoc.element.restify.errors.NotFoundError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>NotImplementedError (cause, message)](#apidoc.element.restify.errors.NotImplementedError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>PayloadTooLargeError (cause, message)](#apidoc.element.restify.errors.PayloadTooLargeError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>PaymentRequiredError (cause, message)](#apidoc.element.restify.errors.PaymentRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>PreconditionFailedError (cause, message)](#apidoc.element.restify.errors.PreconditionFailedError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>PreconditionRequiredError (cause, message)](#apidoc.element.restify.errors.PreconditionRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>ProxyAuthenticationRequiredError (cause, message)](#apidoc.element.restify.errors.ProxyAuthenticationRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>RangeNotSatisfiableError (cause, message)](#apidoc.element.restify.errors.RangeNotSatisfiableError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>RequestExpiredError (cause, message)](#apidoc.element.restify.errors.RequestExpiredError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>RequestHeaderFieldsTooLargeError (cause, message)](#apidoc.element.restify.errors.RequestHeaderFieldsTooLargeError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>RequestThrottledError (cause, message)](#apidoc.element.restify.errors.RequestThrottledError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>RequestTimeoutError (cause, message)](#apidoc.element.restify.errors.RequestTimeoutError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>ResourceNotFoundError (cause, message)](#apidoc.element.restify.errors.ResourceNotFoundError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>RestError (options)](#apidoc.element.restify.errors.RestError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>ServiceUnavailableError (cause, message)](#apidoc.element.restify.errors.ServiceUnavailableError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>TooManyRequestsError (cause, message)](#apidoc.element.restify.errors.TooManyRequestsError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>UnauthorizedError (cause, message)](#apidoc.element.restify.errors.UnauthorizedError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>UnavailableForLegalReasonsError (cause, message)](#apidoc.element.restify.errors.UnavailableForLegalReasonsError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>UnorderedCollectionError (cause, message)](#apidoc.element.restify.errors.UnorderedCollectionError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>UnprocessableEntityError (cause, message)](#apidoc.element.restify.errors.UnprocessableEntityError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>UnsupportedMediaTypeError (cause, message)](#apidoc.element.restify.errors.UnsupportedMediaTypeError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>UpgradeRequiredError (cause, message)](#apidoc.element.restify.errors.UpgradeRequiredError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>UriTooLongError (cause, message)](#apidoc.element.restify.errors.UriTooLongError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>VariantAlsoNegotiatesError (cause, message)](#apidoc.element.restify.errors.VariantAlsoNegotiatesError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>WrongAcceptError (cause, message)](#apidoc.element.restify.errors.WrongAcceptError)
1.  [function <span class="apidocSignatureSpan">restify.errors.</span>codeToHttpError (code, message, body)](#apidoc.element.restify.errors.codeToHttpError)

#### [module restify.formatters](#apidoc.module.restify.formatters)

#### [module restify.plugins](#apidoc.module.restify.plugins)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>CORS (opts)](#apidoc.element.restify.plugins.CORS)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>acceptParser (acceptable)](#apidoc.element.restify.plugins.acceptParser)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>auditLogger (options)](#apidoc.element.restify.plugins.auditLogger)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>authorizationParser (options)](#apidoc.element.restify.plugins.authorizationParser)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>bodyParser (options)](#apidoc.element.restify.plugins.bodyParser)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>conditionalRequest ()](#apidoc.element.restify.plugins.conditionalRequest)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>dateParser (clockSkew)](#apidoc.element.restify.plugins.dateParser)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>fullResponse ()](#apidoc.element.restify.plugins.fullResponse)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>gzipResponse (opts)](#apidoc.element.restify.plugins.gzipResponse)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>jsonBodyParser (options)](#apidoc.element.restify.plugins.jsonBodyParser)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>jsonp ()](#apidoc.element.restify.plugins.jsonp)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>multipartBodyParser (options)](#apidoc.element.restify.plugins.multipartBodyParser)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>queryParser (options)](#apidoc.element.restify.plugins.queryParser)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>requestExpiry (options)](#apidoc.element.restify.plugins.requestExpiry)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>requestLogger (options)](#apidoc.element.restify.plugins.requestLogger)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>sanitizePath (options)](#apidoc.element.restify.plugins.sanitizePath)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>serveStatic (opts)](#apidoc.element.restify.plugins.serveStatic)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>throttle (options)](#apidoc.element.restify.plugins.throttle)
1.  [function <span class="apidocSignatureSpan">restify.plugins.</span>urlEncodedBodyParser (options)](#apidoc.element.restify.plugins.urlEncodedBodyParser)
1.  object <span class="apidocSignatureSpan">restify.plugins.</span>pre

#### [module restify.pre](#apidoc.module.restify.pre)
1.  [function <span class="apidocSignatureSpan">restify.pre.</span>pause ()](#apidoc.element.restify.pre.pause)
1.  [function <span class="apidocSignatureSpan">restify.pre.</span>sanitizePath (options)](#apidoc.element.restify.pre.sanitizePath)
1.  [function <span class="apidocSignatureSpan">restify.pre.</span>userAgentConnection (opts)](#apidoc.element.restify.pre.userAgentConnection)

#### [module restify.router](#apidoc.module.restify.router)
1.  [function <span class="apidocSignatureSpan">restify.</span>router (options)](#apidoc.element.restify.router.router)
1.  [function <span class="apidocSignatureSpan">restify.router.</span>super_ ()](#apidoc.element.restify.router.super_)

#### [module restify.router.prototype](#apidoc.module.restify.router.prototype)
1.  [function <span class="apidocSignatureSpan">restify.router.prototype.</span>find (req, res, callback)](#apidoc.element.restify.router.prototype.find)
1.  [function <span class="apidocSignatureSpan">restify.router.prototype.</span>get (name, req, cb)](#apidoc.element.restify.router.prototype.get)
1.  [function <span class="apidocSignatureSpan">restify.router.prototype.</span>mount (options)](#apidoc.element.restify.router.prototype.mount)
1.  [function <span class="apidocSignatureSpan">restify.router.prototype.</span>render (routeName, params, query)](#apidoc.element.restify.router.prototype.render)
1.  [function <span class="apidocSignatureSpan">restify.router.prototype.</span>toString ()](#apidoc.element.restify.router.prototype.toString)
1.  [function <span class="apidocSignatureSpan">restify.router.prototype.</span>unmount (name)](#apidoc.element.restify.router.prototype.unmount)

#### [module restify.server](#apidoc.module.restify.server)
1.  [function <span class="apidocSignatureSpan">restify.</span>server (options)](#apidoc.element.restify.server.server)
1.  [function <span class="apidocSignatureSpan">restify.server.</span>super_ ()](#apidoc.element.restify.server.super_)

#### [module restify.server.prototype](#apidoc.module.restify.server.prototype)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>_handle (req, res)](#apidoc.element.restify.server.prototype._handle)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>_route (req, res, name, cb)](#apidoc.element.restify.server.prototype._route)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>_run (req, res, route, chain, cb)](#apidoc.element.restify.server.prototype._run)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>_setupRequest (req, res)](#apidoc.element.restify.server.prototype._setupRequest)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>address ()](#apidoc.element.restify.server.prototype.address)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>close (callback)](#apidoc.element.restify.server.prototype.close)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>del (opts)](#apidoc.element.restify.server.prototype.del)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>get (opts)](#apidoc.element.restify.server.prototype.get)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>head (opts)](#apidoc.element.restify.server.prototype.head)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>listen ()](#apidoc.element.restify.server.prototype.listen)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>opts (opts)](#apidoc.element.restify.server.prototype.opts)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>param (name, fn)](#apidoc.element.restify.server.prototype.param)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>patch (opts)](#apidoc.element.restify.server.prototype.patch)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>post (opts)](#apidoc.element.restify.server.prototype.post)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>pre ()](#apidoc.element.restify.server.prototype.pre)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>put (opts)](#apidoc.element.restify.server.prototype.put)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>rm (route)](#apidoc.element.restify.server.prototype.rm)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>toString ()](#apidoc.element.restify.server.prototype.toString)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>use ()](#apidoc.element.restify.server.prototype.use)
1.  [function <span class="apidocSignatureSpan">restify.server.prototype.</span>versionedUse (versions, fn)](#apidoc.element.restify.server.prototype.versionedUse)

#### [module restify.upgrade](#apidoc.module.restify.upgrade)
1.  [function <span class="apidocSignatureSpan">restify.upgrade.</span>InvalidUpgradeStateError (msg)](#apidoc.element.restify.upgrade.InvalidUpgradeStateError)
1.  [function <span class="apidocSignatureSpan">restify.upgrade.</span>createResponse (req, socket, head)](#apidoc.element.restify.upgrade.createResponse)

#### [module restify.utils](#apidoc.module.restify.utils)
1.  [function <span class="apidocSignatureSpan">restify.utils.</span>mergeQs (obj1, obj2)](#apidoc.element.restify.utils.mergeQs)
1.  [function <span class="apidocSignatureSpan">restify.utils.</span>sanitizePath (path)](#apidoc.element.restify.utils.sanitizePath)
1.  [function <span class="apidocSignatureSpan">restify.utils.</span>shallowCopy (obj)](#apidoc.element.restify.utils.shallowCopy)



# <a name="apidoc.module.restify"></a>[module restify](#apidoc.module.restify)

#### <a name="apidoc.element.restify.BadDigestError"></a>[function <span class="apidocSignatureSpan">restify.</span>BadDigestError (cause, message)](#apidoc.element.restify.BadDigestError)
- description and source-code
```javascript
BadDigestError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.BadGatewayError"></a>[function <span class="apidocSignatureSpan">restify.</span>BadGatewayError (cause, message)](#apidoc.element.restify.BadGatewayError)
- description and source-code
```javascript
BadGatewayError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.BadMethodError"></a>[function <span class="apidocSignatureSpan">restify.</span>BadMethodError (cause, message)](#apidoc.element.restify.BadMethodError)
- description and source-code
```javascript
BadMethodError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.BadRequestError"></a>[function <span class="apidocSignatureSpan">restify.</span>BadRequestError (cause, message)](#apidoc.element.restify.BadRequestError)
- description and source-code
```javascript
BadRequestError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.BandwidthLimitExceededError"></a>[function <span class="apidocSignatureSpan">restify.</span>BandwidthLimitExceededError (cause, message)](#apidoc.element.restify.BandwidthLimitExceededError)
- description and source-code
```javascript
BandwidthLimitExceededError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.CORS"></a>[function <span class="apidocSignatureSpan">restify.</span>CORS (opts)](#apidoc.element.restify.CORS)
- description and source-code
```javascript
function cors(opts) {
    assert.optionalObject(opts, 'options');
    opts = opts || {};
    assert.optionalArrayOfString(opts.origins, 'options.origins');
    assert.optionalBool(opts.credentials, 'options.credentials');
    assert.optionalArrayOfString(opts.headers, 'options.headers');

    cors.credentials = opts.credentials;
    cors.origins = opts.origins || ['*'];

    var headers = (opts.headers || []).slice(0);
    var origins = opts.origins || ['*'];

    EXPOSE_HEADERS.forEach(function (h) {
        if (headers.indexOf(h) === -1) {
            headers.push(h);
        }
    });

    // Handler for simple requests
    function restifyCORSSimple(req, res, next) {
        var origin;

        if (!(origin = matchOrigin(req, origins))) {
            next();
            return;
        }

        function corsOnHeader() {
            origin = req.headers.origin;

            if (opts.credentials) {
                res.setHeader(AC_ALLOW_ORIGIN, origin);
                res.setHeader(AC_ALLOW_CREDS, 'true');
            } else {
                res.setHeader(AC_ALLOW_ORIGIN, origin);
            }

            res.setHeader(AC_EXPOSE_HEADERS, headers.join(', '));
        }

        res.once('header', corsOnHeader);
        next();
    }

    return (restifyCORSSimple);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ConflictError"></a>[function <span class="apidocSignatureSpan">restify.</span>ConflictError (cause, message)](#apidoc.element.restify.ConflictError)
- description and source-code
```javascript
ConflictError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ExpectationFailedError"></a>[function <span class="apidocSignatureSpan">restify.</span>ExpectationFailedError (cause, message)](#apidoc.element.restify.ExpectationFailedError)
- description and source-code
```javascript
ExpectationFailedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.FailedDependencyError"></a>[function <span class="apidocSignatureSpan">restify.</span>FailedDependencyError (cause, message)](#apidoc.element.restify.FailedDependencyError)
- description and source-code
```javascript
FailedDependencyError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ForbiddenError"></a>[function <span class="apidocSignatureSpan">restify.</span>ForbiddenError (cause, message)](#apidoc.element.restify.ForbiddenError)
- description and source-code
```javascript
ForbiddenError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.GatewayTimeoutError"></a>[function <span class="apidocSignatureSpan">restify.</span>GatewayTimeoutError (cause, message)](#apidoc.element.restify.GatewayTimeoutError)
- description and source-code
```javascript
GatewayTimeoutError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.GoneError"></a>[function <span class="apidocSignatureSpan">restify.</span>GoneError (cause, message)](#apidoc.element.restify.GoneError)
- description and source-code
```javascript
GoneError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient"></a>[function <span class="apidocSignatureSpan">restify.</span>HttpClient (options)](#apidoc.element.restify.HttpClient)
- description and source-code
```javascript
function HttpClient(options) {
    assert.object(options, 'options');
    assert.optionalObject(options.headers, 'options.headers');
    assert.object(options.log, 'options.log');
    assert.optionalFunc(options.signRequest, 'options.signRequest');
    assert.optionalString(options.socketPath, 'options.socketPath');
    assert.optionalString(options.url, 'options.url');

    EventEmitter.call(this);

    var self = this;

    this.agent = options.agent;
    this.ca = options.ca;
    this.cert = options.cert;
    this.ciphers = options.ciphers;
    this.connectTimeout = options.connectTimeout || false;
    this.requestTimeout = options.requestTimeout || false;
    this.headers = options.headers || {};
    this.log = options.log;

    if (!this.log.serializers) {
        // Ensure logger has a reasonable serializer for 'client_res'
        // and 'client_req' logged in this module.
        this.log = this.log.child({serializers: bunyan.serializers});
    }
    this.key = options.key;
    this.name = options.name || 'HttpClient';
    this.passphrase = options.passphrase;
    this.pfx = options.pfx;

    if (options.rejectUnauthorized !== undefined) {
        this.rejectUnauthorized = options.rejectUnauthorized;
    } else {
        this.rejectUnauthorized = true;
    }

    this.retry = cloneRetryOptions(options.retry);
    this.signRequest = options.signRequest || false;
    this.socketPath = options.socketPath || false;
    this.url = options.url ? url.parse(options.url) : {};

    if (process.env.https_proxy) {
        this.proxy = url.parse(process.env.https_proxy);
    } else if (process.env.http_proxy) {
        this.proxy = url.parse(process.env.http_proxy);
    } else if (options.proxy) {
        this.proxy = options.proxy;
    } else {
        this.proxy = false;
    }

    if (this.proxy && !isProxyForURL(self.url)) {
        this.proxy = false;
    }

    if (options.accept) {
        if (options.accept.indexOf('/') === -1) {
            options.accept = mime.lookup(options.accept);
        }

        this.headers.accept = options.accept;
    }

    if (options.contentType) {
        if (options.contentType.indexOf('/') === -1) {
            options.type = mime.lookup(options.contentType);
        }

        this.headers['content-type'] = options.contentType;
    }

    if (options.userAgent !== false) {
        this.headers['user-agent'] = options.userAgent ||
            defaultUserAgent();
    }

    if (options.version) {
        this.headers['accept-version'] = options.version;
    }

    if (this.agent === undefined) {
        var Agent;
        var maxSockets;

        if (this.proxy) {
            if (this.url.protocol === 'https:') {
                if (this.proxy.protocol === 'https:') {
                    Agent = tunnelAgent.httpsOverHttps;
                } else {
                    Agent = tunnelAgent.httpsOverHttp;
                }
            } else {
                if (this.proxy.protocol === 'https:') {
                    Agent = tunnelAgent.httpOverHttps;
                } else {
                    Agent = tunnelAgent.httpOverHttp;
                }
            }
        } else if (this.url.protocol === 'https:') {
            Agent = KeepAliveAgentSecure;
            maxSockets = httpsMaxSockets;
        } else {
            Agent = KeepAliveAgent;
            maxSockets = httpMaxSockets;
        }

        if (this.proxy) {
            this.agent = new Agent({
                proxy: self.proxy,
                rejectUnauthorized: self.rejectUnauthorized,
                ca: self.ca
            });
        } else {
            this.agent = new Agent({
                cert: self.cert,
                ca: self.ca,
                ciphers: self.ciphers,
                key: self.key,
                maxSockets: maxSockets,

                // require('keep-alive-agent')
                maxKeepAliveRequests: 0,
                maxKeepAliveTime: 0,

                // native keepalive
                keepAliveMsecs: 1000,
                keepAlive: true,

                passphrase: self.passp ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpError"></a>[function <span class="apidocSignatureSpan">restify.</span>HttpError (options)](#apidoc.element.restify.HttpError)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpError.super_"></a>[function <span class="apidocSignatureSpan">restify.</span>HttpError.super_ ()](#apidoc.element.restify.HttpError.super_)
- description and source-code
```javascript
function WError()
{
	var args, obj, parsed, options;

	args = Array.prototype.slice.call(arguments, 0);
	if (!(this instanceof WError)) {
		obj = Object.create(WError.prototype);
		WError.apply(obj, args);
		return (obj);
	}

	parsed = parseConstructorArguments({
	    'argv': args,
	    'strict': false
	});

	options = parsed.options;
	options['skipCauseMessage'] = true;
	VError.call(this, options, '%s', parsed.shortmessage);

	return (this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpVersionNotSupportedError"></a>[function <span class="apidocSignatureSpan">restify.</span>HttpVersionNotSupportedError (cause, message)](#apidoc.element.restify.HttpVersionNotSupportedError)
- description and source-code
```javascript
HttpVersionNotSupportedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ImATeapotError"></a>[function <span class="apidocSignatureSpan">restify.</span>ImATeapotError (cause, message)](#apidoc.element.restify.ImATeapotError)
- description and source-code
```javascript
ImATeapotError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InsufficientStorageError"></a>[function <span class="apidocSignatureSpan">restify.</span>InsufficientStorageError (cause, message)](#apidoc.element.restify.InsufficientStorageError)
- description and source-code
```javascript
InsufficientStorageError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InternalError"></a>[function <span class="apidocSignatureSpan">restify.</span>InternalError (cause, message)](#apidoc.element.restify.InternalError)
- description and source-code
```javascript
InternalError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
...
        emittedError = true;
    } else {
        res.send(arg);
    }
    done = true;
} else if (typeof (arg) === 'string') { // GH-193, allow redirect
    if (req._rstfy_chained_route) {
        var _e = new errors.InternalError();
        log.error({
            err: _e
        }, 'Multiple next("chain") calls not ' +
            'supported');
        res.send(_e);
        return (false);
    }
...
```

#### <a name="apidoc.element.restify.InternalServerError"></a>[function <span class="apidocSignatureSpan">restify.</span>InternalServerError (cause, message)](#apidoc.element.restify.InternalServerError)
- description and source-code
```javascript
InternalServerError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InvalidArgumentError"></a>[function <span class="apidocSignatureSpan">restify.</span>InvalidArgumentError (cause, message)](#apidoc.element.restify.InvalidArgumentError)
- description and source-code
```javascript
InvalidArgumentError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InvalidContentError"></a>[function <span class="apidocSignatureSpan">restify.</span>InvalidContentError (cause, message)](#apidoc.element.restify.InvalidContentError)
- description and source-code
```javascript
InvalidContentError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InvalidCredentialsError"></a>[function <span class="apidocSignatureSpan">restify.</span>InvalidCredentialsError (cause, message)](#apidoc.element.restify.InvalidCredentialsError)
- description and source-code
```javascript
InvalidCredentialsError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InvalidHeaderError"></a>[function <span class="apidocSignatureSpan">restify.</span>InvalidHeaderError (cause, message)](#apidoc.element.restify.InvalidHeaderError)
- description and source-code
```javascript
InvalidHeaderError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InvalidVersionError"></a>[function <span class="apidocSignatureSpan">restify.</span>InvalidVersionError (cause, message)](#apidoc.element.restify.InvalidVersionError)
- description and source-code
```javascript
InvalidVersionError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.JsonClient"></a>[function <span class="apidocSignatureSpan">restify.</span>JsonClient (options)](#apidoc.element.restify.JsonClient)
- description and source-code
```javascript
function JsonClient(options) {
    assert.object(options, 'options');

    options.accept = 'application/json';
    options.name = options.name || 'JsonClient';
    options.contentType = 'application/json';

    StringClient.call(this, options);

    this._super = StringClient.prototype;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.LengthRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>LengthRequiredError (cause, message)](#apidoc.element.restify.LengthRequiredError)
- description and source-code
```javascript
LengthRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.LockedError"></a>[function <span class="apidocSignatureSpan">restify.</span>LockedError (cause, message)](#apidoc.element.restify.LockedError)
- description and source-code
```javascript
LockedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.LoopDetectedError"></a>[function <span class="apidocSignatureSpan">restify.</span>LoopDetectedError (cause, message)](#apidoc.element.restify.LoopDetectedError)
- description and source-code
```javascript
LoopDetectedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.MethodNotAllowedError"></a>[function <span class="apidocSignatureSpan">restify.</span>MethodNotAllowedError (cause, message)](#apidoc.element.restify.MethodNotAllowedError)
- description and source-code
```javascript
MethodNotAllowedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.MisdirectedRequestError"></a>[function <span class="apidocSignatureSpan">restify.</span>MisdirectedRequestError (cause, message)](#apidoc.element.restify.MisdirectedRequestError)
- description and source-code
```javascript
MisdirectedRequestError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.MissingParameterError"></a>[function <span class="apidocSignatureSpan">restify.</span>MissingParameterError (cause, message)](#apidoc.element.restify.MissingParameterError)
- description and source-code
```javascript
MissingParameterError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NetworkAuthenticationRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>NetworkAuthenticationRequiredError (cause, message)](#apidoc.element.restify.NetworkAuthenticationRequiredError)
- description and source-code
```javascript
NetworkAuthenticationRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NotAcceptableError"></a>[function <span class="apidocSignatureSpan">restify.</span>NotAcceptableError (cause, message)](#apidoc.element.restify.NotAcceptableError)
- description and source-code
```javascript
NotAcceptableError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NotAuthorizedError"></a>[function <span class="apidocSignatureSpan">restify.</span>NotAuthorizedError (cause, message)](#apidoc.element.restify.NotAuthorizedError)
- description and source-code
```javascript
NotAuthorizedError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NotExtendedError"></a>[function <span class="apidocSignatureSpan">restify.</span>NotExtendedError (cause, message)](#apidoc.element.restify.NotExtendedError)
- description and source-code
```javascript
NotExtendedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NotFoundError"></a>[function <span class="apidocSignatureSpan">restify.</span>NotFoundError (cause, message)](#apidoc.element.restify.NotFoundError)
- description and source-code
```javascript
NotFoundError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NotImplementedError"></a>[function <span class="apidocSignatureSpan">restify.</span>NotImplementedError (cause, message)](#apidoc.element.restify.NotImplementedError)
- description and source-code
```javascript
NotImplementedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.PayloadTooLargeError"></a>[function <span class="apidocSignatureSpan">restify.</span>PayloadTooLargeError (cause, message)](#apidoc.element.restify.PayloadTooLargeError)
- description and source-code
```javascript
PayloadTooLargeError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.PaymentRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>PaymentRequiredError (cause, message)](#apidoc.element.restify.PaymentRequiredError)
- description and source-code
```javascript
PaymentRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.PreconditionFailedError"></a>[function <span class="apidocSignatureSpan">restify.</span>PreconditionFailedError (cause, message)](#apidoc.element.restify.PreconditionFailedError)
- description and source-code
```javascript
PreconditionFailedError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.PreconditionRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>PreconditionRequiredError (cause, message)](#apidoc.element.restify.PreconditionRequiredError)
- description and source-code
```javascript
PreconditionRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ProxyAuthenticationRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>ProxyAuthenticationRequiredError (cause, message)](#apidoc.element.restify.ProxyAuthenticationRequiredError)
- description and source-code
```javascript
ProxyAuthenticationRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RangeNotSatisfiableError"></a>[function <span class="apidocSignatureSpan">restify.</span>RangeNotSatisfiableError (cause, message)](#apidoc.element.restify.RangeNotSatisfiableError)
- description and source-code
```javascript
RangeNotSatisfiableError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RequestExpiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>RequestExpiredError (cause, message)](#apidoc.element.restify.RequestExpiredError)
- description and source-code
```javascript
RequestExpiredError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RequestHeaderFieldsTooLargeError"></a>[function <span class="apidocSignatureSpan">restify.</span>RequestHeaderFieldsTooLargeError (cause, message)](#apidoc.element.restify.RequestHeaderFieldsTooLargeError)
- description and source-code
```javascript
RequestHeaderFieldsTooLargeError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RequestThrottledError"></a>[function <span class="apidocSignatureSpan">restify.</span>RequestThrottledError (cause, message)](#apidoc.element.restify.RequestThrottledError)
- description and source-code
```javascript
RequestThrottledError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RequestTimeoutError"></a>[function <span class="apidocSignatureSpan">restify.</span>RequestTimeoutError (cause, message)](#apidoc.element.restify.RequestTimeoutError)
- description and source-code
```javascript
RequestTimeoutError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ResourceNotFoundError"></a>[function <span class="apidocSignatureSpan">restify.</span>ResourceNotFoundError (cause, message)](#apidoc.element.restify.ResourceNotFoundError)
- description and source-code
```javascript
ResourceNotFoundError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RestError"></a>[function <span class="apidocSignatureSpan">restify.</span>RestError (options)](#apidoc.element.restify.RestError)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ServiceUnavailableError"></a>[function <span class="apidocSignatureSpan">restify.</span>ServiceUnavailableError (cause, message)](#apidoc.element.restify.ServiceUnavailableError)
- description and source-code
```javascript
ServiceUnavailableError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.StringClient"></a>[function <span class="apidocSignatureSpan">restify.</span>StringClient (options)](#apidoc.element.restify.StringClient)
- description and source-code
```javascript
function StringClient(options) {
    assert.object(options, 'options');
    assert.optionalObject(options.gzip, 'options.gzip');

    options.accept = options.accept || 'text/plain';
    options.name = options.name || 'StringClient';
    options.contentType =
        options.contentType || 'application/x-www-form-urlencoded';

    HttpClient.call(this, options);
    this.gzip = options.gzip;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.TooManyRequestsError"></a>[function <span class="apidocSignatureSpan">restify.</span>TooManyRequestsError (cause, message)](#apidoc.element.restify.TooManyRequestsError)
- description and source-code
```javascript
TooManyRequestsError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UnauthorizedError"></a>[function <span class="apidocSignatureSpan">restify.</span>UnauthorizedError (cause, message)](#apidoc.element.restify.UnauthorizedError)
- description and source-code
```javascript
UnauthorizedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UnavailableForLegalReasonsError"></a>[function <span class="apidocSignatureSpan">restify.</span>UnavailableForLegalReasonsError (cause, message)](#apidoc.element.restify.UnavailableForLegalReasonsError)
- description and source-code
```javascript
UnavailableForLegalReasonsError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UnorderedCollectionError"></a>[function <span class="apidocSignatureSpan">restify.</span>UnorderedCollectionError (cause, message)](#apidoc.element.restify.UnorderedCollectionError)
- description and source-code
```javascript
UnorderedCollectionError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UnprocessableEntityError"></a>[function <span class="apidocSignatureSpan">restify.</span>UnprocessableEntityError (cause, message)](#apidoc.element.restify.UnprocessableEntityError)
- description and source-code
```javascript
UnprocessableEntityError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UnsupportedMediaTypeError"></a>[function <span class="apidocSignatureSpan">restify.</span>UnsupportedMediaTypeError (cause, message)](#apidoc.element.restify.UnsupportedMediaTypeError)
- description and source-code
```javascript
UnsupportedMediaTypeError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UpgradeRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>UpgradeRequiredError (cause, message)](#apidoc.element.restify.UpgradeRequiredError)
- description and source-code
```javascript
UpgradeRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UriTooLongError"></a>[function <span class="apidocSignatureSpan">restify.</span>UriTooLongError (cause, message)](#apidoc.element.restify.UriTooLongError)
- description and source-code
```javascript
UriTooLongError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.VariantAlsoNegotiatesError"></a>[function <span class="apidocSignatureSpan">restify.</span>VariantAlsoNegotiatesError (cause, message)](#apidoc.element.restify.VariantAlsoNegotiatesError)
- description and source-code
```javascript
VariantAlsoNegotiatesError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.WrongAcceptError"></a>[function <span class="apidocSignatureSpan">restify.</span>WrongAcceptError (cause, message)](#apidoc.element.restify.WrongAcceptError)
- description and source-code
```javascript
WrongAcceptError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.acceptParser"></a>[function <span class="apidocSignatureSpan">restify.</span>acceptParser (acceptable)](#apidoc.element.restify.acceptParser)
- description and source-code
```javascript
function acceptParser(acceptable) {
    if (!Array.isArray(acceptable)) {
        acceptable = [acceptable];
    }
    assert.arrayOfString(acceptable, 'acceptable');

    acceptable = acceptable.filter(function (a) {
        return (a);
    }).map(function (a) {
            return ((a.indexOf('/') === -1) ? mime.lookup(a) : a);
        }).filter(function (a) {
            return (a);
        });

    var e = new NotAcceptableError('Server accepts: ' + acceptable.join());

    function parseAccept(req, res, next) {
        if (req.accepts(acceptable)) {
            next();
            return;
        }

        res.json(e);
        next(false);
    }

    return (parseAccept);
}
```
- example usage
```shell
...
'''javascript
var restify = require('restify');

var server = restify.createServer({
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});
...
```

#### <a name="apidoc.element.restify.auditLogger"></a>[function <span class="apidocSignatureSpan">restify.</span>auditLogger (options)](#apidoc.element.restify.auditLogger)
- description and source-code
```javascript
function auditLogger(options) {
    assert.object(options, 'options');
    assert.object(options.log, 'options.log');
    var errSerializer = bunyan.stdSerializers.err;

    if (options.log.serializers && options.log.serializers.err) {
        errSerializer = options.log.serializers.err;
    }

    var log = options.log.child({
        audit: true,
        serializers: {
            err: errSerializer,
            req: function auditRequestSerializer(req) {
                if (!req) {
                    return (false);
                }

                var timers = {};
                (req.timers || []).forEach(function (time) {
                    var t = time.time;
                    var _t = Math.floor((1000000 * t[0]) +
                        (t[1] / 1000));
                    timers[time.name] = _t;
                });
                return ({
                    // account for native and queryParser plugin usage
                    query: (typeof req.query === 'function') ?
                            req.query() : req.query,
                    method: req.method,
                    url: req.url,
                    headers: req.headers,
                    httpVersion: req.httpVersion,
                    trailers: req.trailers,
                    version: req.version(),
                    body: options.body === true ?
                        req.body : undefined,
                    timers: timers
                });
            },
            res: function auditResponseSerializer(res) {
                if (!res) {
                    return (false);
                }


                var body;

                if (options.body === true) {
                    if (res._body instanceof HttpError) {
                        body = res._body.body;
                    } else {
                        body = res._body;
                    }
                }

                return ({
                    statusCode: res.statusCode,
                    headers: res._headers,
                    trailer: res._trailer || false,
                    body: body
                });
            }
        }
    });

    function audit(req, res, route, err) {
        var latency = res.get('Response-Time');

        if (typeof (latency) !== 'number') {
            latency = Date.now() - req._time;
        }

        var obj = {
            remoteAddress: req.connection.remoteAddress,
            remotePort: req.connection.remotePort,
            req_id: req.getId(),
            req: req,
            res: res,
            err: err,
            latency: latency,
            secure: req.secure,
            _audit: true
        };

        log.info(obj, 'handled: %d', res.statusCode);

        return (true);
    }

    return (audit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.authorizationParser"></a>[function <span class="apidocSignatureSpan">restify.</span>authorizationParser (options)](#apidoc.element.restify.authorizationParser)
- description and source-code
```javascript
function authorizationParser(options) {

    function parseAuthorization(req, res, next) {
        req.authorization = {};
        req.username = 'anonymous';

        if (!req.headers.authorization) {
            return (next());
        }

        var pieces = req.headers.authorization.split(' ', 2);

        if (!pieces || pieces.length !== 2) {
            var e = new InvalidHeaderError('BasicAuth content ' +
                'is invalid.');
            return (next(e));
        }

        req.authorization.scheme = pieces[0];
        req.authorization.credentials = pieces[1];

        try {
            switch (pieces[0].toLowerCase()) {
                case 'basic':
                    req.authorization.basic = parseBasic(pieces[1]);
                    req.username = req.authorization.basic.username;
                    break;

                case 'signature':
                    req.authorization.signature =
                        parseSignature(req, options);
                    req.username =
                        req.authorization.signature.keyId;
                    break;

                default:
                    break;
            }
        } catch (e2) {
            return (next(e2));
        }

        return (next());
    }

    return (parseAuthorization);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.bodyParser"></a>[function <span class="apidocSignatureSpan">restify.</span>bodyParser (options)](#apidoc.element.restify.bodyParser)
- description and source-code
```javascript
function bodyParser(options) {
    assert.optionalObject(options, 'options');
    options = options || {};
    options.bodyReader = true;

    var read = bodyReader(options);
    var parseForm = formParser(options);
    var parseJson = jsonParser(options);
    var parseMultipart = multipartParser(options);
    var parseFieldedText = fieldedTextParser(options);

    function parseBody(req, res, next) {
        // Allow use of 'requestBodyOnGet' flag to allow for merging of
        // the request body of a GET request into req.params
        if (req.method === 'HEAD') {
            next();
            return;
        }

        if (req.method === 'GET') {
            if (!options.requestBodyOnGet) {
                next();
                return;
            }
        }

        if (req.contentLength() === 0 && !req.isChunked()) {
            next();
            return;
        }

        var parser;
        var type = req.contentType().toLowerCase();

        switch (type) {
            case 'application/json':
                parser = parseJson[0];
                break;
            case 'application/x-www-form-urlencoded':
                parser = parseForm[0];
                break;
            case 'multipart/form-data':
                parser = parseMultipart;
                break;
            case 'text/tsv':
                parser = parseFieldedText;
                break;
            case 'text/tab-separated-values':
                parser = parseFieldedText;
                break;
            case 'text/csv':
                parser = parseFieldedText;
                break;

            default:
                break;
        }

        if (parser) {
            parser(req, res, next);
        } else if (options && options.rejectUnknown) {
            next(new UnsupportedMediaTypeError(type));
        } else {
            next();
        }
    }

    return ([read, parseBody]);
}
```
- example usage
```shell
...

var server = restify.createServer({
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});

server.listen(8080, function () {
...
```

#### <a name="apidoc.element.restify.bunyan.RequestCaptureStream"></a>[function <span class="apidocSignatureSpan">restify.</span>bunyan.RequestCaptureStream (opts)](#apidoc.element.restify.bunyan.RequestCaptureStream)
- description and source-code
```javascript
function RequestCaptureStream(opts) {
    assert.object(opts, 'options');
    assert.optionalObject(opts.stream, 'options.stream');
    assert.optionalArrayOfObject(opts.streams, 'options.streams');
    assert.optionalNumber(opts.level, 'options.level');
    assert.optionalNumber(opts.maxRecords, 'options.maxRecords');
    assert.optionalNumber(opts.maxRequestIds, 'options.maxRequestIds');
    assert.optionalBool(opts.dumpDefault, 'options.dumpDefault');

    var self = this;
    Stream.call(this);

    this.level = opts.level ? bunyan.resolveLevel(opts.level) : bunyan.WARN;
    this.limit = opts.maxRecords || 100;
    this.maxRequestIds = opts.maxRequestIds || 1000;
    this.requestMap = LRU({
        max: self.maxRequestIds
    });
    this.dumpDefault = opts.dumpDefault;

    this._offset = -1;
    this._rings = [];

    this.streams = [];

    if (opts.stream) {
        appendStream(this.streams, opts.stream);
    }

    if (opts.streams) {
        opts.streams.forEach(appendStream.bind(null, this.streams));
    }

    this.haveNonRawStreams = false;

    for (var i = 0; i < this.streams.length; i++) {
        if (!this.streams[i].raw) {
            this.haveNonRawStreams = true;
            break;
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.codeToHttpError"></a>[function <span class="apidocSignatureSpan">restify.</span>codeToHttpError (code, message, body)](#apidoc.element.restify.codeToHttpError)
- description and source-code
```javascript
function codeToHttpError(code, message, body) {
    var err;
    var name = codeToErrorName(code);

    if (!name) {
        err = new HttpError({
            statusCode: code,
            message: message,
            body: body
        });
        err.name = 'Http' + code + 'Error';
    } else {
        err = new module.exports[name]({
            body: body,
            message: message,
            constructorOpt: codeToHttpError,
            statusCode: code
        });
    }

    return (err);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.conditionalRequest"></a>[function <span class="apidocSignatureSpan">restify.</span>conditionalRequest ()](#apidoc.element.restify.conditionalRequest)
- description and source-code
```javascript
function conditionalRequest() {
    var chain = [
        checkIfMatch,
        checkIfNoneMatch,
        checkIfModified,
        checkIfUnmodified
    ];
    return (chain);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.createClient"></a>[function <span class="apidocSignatureSpan">restify.</span>createClient (options)](#apidoc.element.restify.createClient)
- description and source-code
```javascript
function createClient(options) {
    if (typeof (options) === 'string') {
        options = {
            url: options
        };
    }

    var assert = require('assert-plus');
    var bunyan = require('./bunyan_helper');
    var clients = require('./clients');

    assert.object(options, 'options');

    var client;
    var opts = shallowCopy(options);
    opts.agent = options.agent;
    opts.name = opts.name || 'restify';
    opts.type = opts.type || 'application/octet-stream';
    opts.log = opts.log || bunyan.createLogger(opts.name);

    switch (opts.type) {
        case 'json':
            client = new clients.JsonClient(opts);
            break;

        case 'string':
            client = new clients.StringClient(opts);
            break;

        case 'http':
        default:
            client = new clients.HttpClient(opts);
            break;
    }

    return (client);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.createHttpClient"></a>[function <span class="apidocSignatureSpan">restify.</span>createHttpClient (options)](#apidoc.element.restify.createHttpClient)
- description and source-code
```javascript
function createHttpClient(options) {
    if (typeof (options) === 'string') {
        options = {
            url: options
        };
    }

    options = options ? shallowCopy(options) : {};
    options.type = 'http';
    return (createClient(options));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.createJSONClient"></a>[function <span class="apidocSignatureSpan">restify.</span>createJSONClient (options)](#apidoc.element.restify.createJSONClient)
- description and source-code
```javascript
function createJsonClient(options) {
    if (typeof (options) === 'string') {
        options = {
            url: options
        };
    }

    options = options ? shallowCopy(options) : {};
    options.type = 'json';
    return (createClient(options));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.createJsonClient"></a>[function <span class="apidocSignatureSpan">restify.</span>createJsonClient (options)](#apidoc.element.restify.createJsonClient)
- description and source-code
```javascript
function createJsonClient(options) {
    if (typeof (options) === 'string') {
        options = {
            url: options
        };
    }

    options = options ? shallowCopy(options) : {};
    options.type = 'json';
    return (createClient(options));
}
```
- example usage
```shell
...

## Client

'''javascript
var assert = require('assert');
var restify = require('restify');

var client = restify.createJsonClient({
url: 'http://localhost:8080',
version: '~1.0'
});

client.get('/echo/mark', function (err, req, res, obj) {
assert.ifError(err);
console.log('Server returned: %j', obj);
...
```

#### <a name="apidoc.element.restify.createServer"></a>[function <span class="apidocSignatureSpan">restify.</span>createServer (options)](#apidoc.element.restify.createServer)
- description and source-code
```javascript
function createServer(options) {
    var bunyan = require('./bunyan_helper');
    var InternalError = require('./errors').InternalError;
    var Router = require('./router');
    var Server = require('./server');

    var opts = shallowCopy(options || {});
    var server;

    opts.name = opts.name || 'restify';
    opts.log = opts.log || bunyan.createLogger(opts.name);
    opts.router = opts.router || new Router(opts);

    server = new Server(opts);

    if (server.handleUncaughtExceptions) {
        server.on('uncaughtException', function (req, res, route, e) {
            if (this.listeners('uncaughtException').length > 1 ||
                res.headersSent) {
                return (false);
            }

            res.send(new InternalError(e, e.message || 'unexpected error'));
            return (true);
        });
    }

    return (server);
}
```
- example usage
```shell
...
# Usage

## Server

'''javascript
var restify = require('restify');

var server = restify.createServer({
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());
...
```

#### <a name="apidoc.element.restify.createStringClient"></a>[function <span class="apidocSignatureSpan">restify.</span>createStringClient (options)](#apidoc.element.restify.createStringClient)
- description and source-code
```javascript
function createStringClient(options) {
    if (typeof (options) === 'string') {
        options = {
            url: options
        };
    }

    options = options ? shallowCopy(options) : {};
    options.type = 'string';
    return (createClient(options));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.dateParser"></a>[function <span class="apidocSignatureSpan">restify.</span>dateParser (clockSkew)](#apidoc.element.restify.dateParser)
- description and source-code
```javascript
function dateParser(clockSkew) {
    if (!clockSkew) {
        clockSkew = 300;
    }
    assert.number(clockSkew, 'clockSkew');

    clockSkew = clockSkew * 1000;

    function parseDate(req, res, next) {
        if (!req.headers.date) {
            return (next());
        }

        var e;
        var date = req.headers.date;
        var log = req.log;

        try {
            var now = Date.now();
            var sent = new Date(date).getTime();

            if (log.trace()) {
                log.trace({
                    allowedSkew: clockSkew,
                    now: now,
                    sent: sent
                }, 'Checking clock skew');
            }

            if ((now - sent) > clockSkew) {
                e = new RequestExpiredError(OLD_MSG, date);
                return (next(e));
            }


        } catch (err) {
            log.trace({
                err: err
            }, 'Bad Date header: %s', date);

            e = new InvalidHeaderError(BAD_MSG, date);
            return (next(e));
        }

        return (next());
    }

    return (parseDate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.fullResponse"></a>[function <span class="apidocSignatureSpan">restify.</span>fullResponse ()](#apidoc.element.restify.fullResponse)
- description and source-code
```javascript
function fullResponse() {
    function restifyResponseHeaders(req, res, next) {
        res.once('header', function () {

            // Restify 1.0 compatibility
            if (res.defaultResponseFormatters) {
                res.defaultResponseFormatters(res._data);
            }

            res.emit('beforeSend', res._data, res._body);

            // end backwards-compatibility
            return (setHeaders(req, res));
        });

        return (next());
    }

    return (restifyResponseHeaders);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.gzipResponse"></a>[function <span class="apidocSignatureSpan">restify.</span>gzipResponse (opts)](#apidoc.element.restify.gzipResponse)
- description and source-code
```javascript
function gzipResponse(opts) {
    assert.optionalObject(opts, 'options');

    function gzip(req, res, next) {
        if (!req.acceptsEncoding('gzip')) {
            next();
            return;
        }

        var gz = zlib.createGzip(opts);

        gz.on('data', res.write.bind(res));
        gz.once('end', res.end.bind(res));
        gz.on('drain', res.emit.bind(res, 'drain'));

        var origWrite = res.write;
        var origEnd = res.end;
        var origWriteHead = res.writeHead;
        res.handledGzip = function _handledGzip() {
            res.write = origWrite;
            res.end = origEnd;
            res.writeHead = origWriteHead;
        };

        res.write = gz.write.bind(gz);
        res.end = gz.end.bind(gz);

        res.writeHead = _writeHead.bind(res, res.writeHead);
        res.setHeader('Content-Encoding', 'gzip');
        next();
    }

    return (gzip);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.httpDate"></a>[function <span class="apidocSignatureSpan">restify.</span>httpDate (now)](#apidoc.element.restify.httpDate)
- description and source-code
```javascript
function httpDate(now) {
    if (!now) {
        now = new Date();
    }

    return (now.toUTCString());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.jsonBodyParser"></a>[function <span class="apidocSignatureSpan">restify.</span>jsonBodyParser (options)](#apidoc.element.restify.jsonBodyParser)
- description and source-code
```javascript
function jsonBodyParser(options) {
    assert.optionalObject(options, 'options');
    options = options || {};

    var override = options.overrideParams;

    function parseJson(req, res, next) {
        if (req.getContentType() !== 'application/json' || !req.body) {
            next();
            return;
        }

        var params;

        try {
            params = JSON.parse(req.body, options.reviver);
        } catch (e) {
            next(new errors.InvalidContentError('Invalid JSON: ' +
                e.message));
            return;
        }

        if (options.mapParams !== false) {
            if (Array.isArray(params)) {
                req.params = params;
            } else if (typeof (params) === 'object' && params !== null) {
                Object.keys(params).forEach(function (k) {
                    var p = req.params[k];

                    if (p && !override) {
                        return (false);
                    }
                    req.params[k] = params[k];
                    return (true);
                });
            } else {
                req.params = params || req.params;
            }
        } else {
            req._body = req.body;
        }

        req.body = params;

        next();
    }

    var chain = [];

    if (!options.bodyReader) {
        chain.push(bodyReader(options));
    }
    chain.push(parseJson);
    return (chain);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.jsonp"></a>[function <span class="apidocSignatureSpan">restify.</span>jsonp ()](#apidoc.element.restify.jsonp)
- description and source-code
```javascript
function jsonp() {
    function _jsonp(req, res, next) {
        var q = req.getQuery();

        // If the query plugin wasn't used, we need to hack it in now
        if (typeof (q) === 'string') {
            req.query = qs.parse(q);
        }

        if (req.query.callback || req.query.jsonp) {
            res.setHeader('Content-Type', 'application/javascript');
        }

        next();
    }

    return (_jsonp);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.multipartBodyParser"></a>[function <span class="apidocSignatureSpan">restify.</span>multipartBodyParser (options)](#apidoc.element.restify.multipartBodyParser)
- description and source-code
```javascript
function multipartBodyParser(options) {
    if (!options) {
        options = {};
    }
    assert.object(options, 'options');
    assert.optionalBool(options.overrideParams, 'options.overrideParams');
    assert.optionalBool(options.multiples, 'options.multiples');
    assert.optionalBool(options.keepExtensions, 'options.keepExtensions');
    assert.optionalString(options.uploadDir, 'options.uploadDir');
    assert.optionalNumber(options.maxFieldsSize, 'options.maxFieldsSize');
    assert.optionalString(options.hash, 'options.hash');
    assert.optionalFunc(options.multipartFileHandler,
                        'options.multipartFileHandler');
    assert.optionalFunc(options.multipartHandler, 'options.multipartHandler');
    assert.optionalBool(options.mapParams, 'options.mapParams');
    assert.optionalBool(options.mapFiles, 'options.mapFiles');

    var override = options.overrideParams;

    function parseMultipartBody(req, res, next) {
        next = once(next);

        if (req.getContentType() !== 'multipart/form-data' ||
            (req.getContentLength() === 0 && !req.isChunked())) {
            return (next());
        }

        var form = new formidable.IncomingForm();

        // enable multiple files on a single upload field
        // (html5 multiple attribute)
        form.multiples = options.multiples || false;
        form.keepExtensions = options.keepExtensions ? true : false;

        if (options.uploadDir) {
            form.uploadDir = options.uploadDir;
        }

        if (options.maxFieldsSize) {
            form.maxFieldsSize = options.maxFieldsSize;
        }

        if (options.hash) {
            form.hash = options.hash;
        }

        form.onPart = function onPart(part) {
            if (part.filename && options.multipartFileHandler) {
                options.multipartFileHandler(part, req);
            } else if (!part.filename && options.multipartHandler) {
                options.multipartHandler(part, req);
            } else {
                form.handlePart(part);
            }
        };

        form.parse(req, function (err, fields, files) {
            if (err) {
                return (next(new errors.BadRequestError(err.message)));
            }

            req.body = fields;
            req.files = files;

            if (options.mapParams !== false) {
                Object.keys(fields).forEach(function (k) {
                    if (req.params[k] && !override) {
                        return;
                    }

                    req.params[k] = fields[k];
                });

                if (options.mapFiles) {
                    var barrier = vasync.barrier();
                    barrier.on('drain', function () {
                        return next();
                    });

                    barrier.start('fs');
                    Object.keys(files).forEach(function (f) {
                        if (req.params[f] && !override) {
                            return;
                        }
                        barrier.start('fs' + f);
                        fs.readFile(files[f].path, function (ex, data) {
                            barrier.done('fs' + f);
<span class="apidocCodeCommentSpan">                            /*
                             * We want to stop the request here, if there's an
                             * error trying to read the file from disk.
                             * Ideally we'd like to stop the other oustanding
                             * file reads too, but there's no way to cancel in
                             * flight fs reads.  So we just return an error, and
                             * be grudgingly let the other file reads finish.
                             */
</span>                            if (ex) {
                                return next(new errors.InternalError(ex,
                                         'unable to read file' + f));
                            }
                            req.params[f] = data;
                            return (true);
                        });
                    });
                    ba ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.queryParser"></a>[function <span class="apidocSignatureSpan">restify.</span>queryParser (options)](#apidoc.element.restify.queryParser)
- description and source-code
```javascript
function queryParser(options) {
    if (!options) {
        options = {};
    }
    assert.object(options, 'options');

<span class="apidocCodeCommentSpan">    /*
     * Releases of restify 4.x up to 4.1.1 used qs@3 which effectively defaulted
     * to 'plainObjects=true' and 'allowDots=true'. To maintain backward
     * compatibility for the restify 4.x stream while using the latest qs
     * version, we need to maintain those defaults. Note that restify-plugins
     * changes back to the pre-restify-4.x behaviour. See test/query.test.js
     * for more details.
     */
</span>    var qsOptions = {
        plainObjects: true,
        allowDots: true
    };
    Object.keys(EXPOSED_QS_OPTIONS).forEach(function (k) {
        EXPOSED_QS_OPTIONS[k](options[k], k); // assert type of this option

        if (options.hasOwnProperty(k)) {
            qsOptions[k] = options[k];
        }
    });

    function parseQueryString(req, res, next) {
        if (!req.getQuery()) {
            req.query = {};
            return (next());
        }

        req.query = qs.parse(req.getQuery(), qsOptions);

        if (options.mapParams !== false) {
            Object.keys(req.query).forEach(function (k) {
                if (req.params[k] && !options.overrideParams) {
                    return (false);
                }

                req.params[k] = req.query[k];
                return (true);
            });
        }

        return (next());
    }

    return (parseQueryString);
}
```
- example usage
```shell
...
var restify = require('restify');

var server = restify.createServer({
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});
...
```

#### <a name="apidoc.element.restify.realizeUrl"></a>[function <span class="apidocSignatureSpan">restify.</span>realizeUrl (pattern, params)](#apidoc.element.restify.realizeUrl)
- description and source-code
```javascript
function realizeUrl(pattern, params) {
    var p = pattern.replace(/\/:([^/]+)/g, function (match, k) {
        return (params.hasOwnProperty(k) ? '/' + params[k] : match);
    });


    return (require('./utils').sanitizePath(p));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.requestExpiry"></a>[function <span class="apidocSignatureSpan">restify.</span>requestExpiry (options)](#apidoc.element.restify.requestExpiry)
- description and source-code
```javascript
function requestExpiry(options) {
    assert.object(options, 'options');
    assert.string(options.header, 'options.header');
    var headerKey = options.header;

    return function (req, res, next) {
        var expiry = req.headers[headerKey];

        if (expiry) {
            var expiryTime = Number(expiry);

            // The request has expired
            if (Date.now() > expiryTime) {
                return next(new GatewayTimeoutError('Request has expired'));
            }
        }

        // Happy case
        return next();
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.requestLogger"></a>[function <span class="apidocSignatureSpan">restify.</span>requestLogger (options)](#apidoc.element.restify.requestLogger)
- description and source-code
```javascript
function requestLogger(options) {
    assert.optionalObject(options);
    options = options || {};

    var props;

    if (options.properties) {
        props = shallowCopy(options.properties);
    } else {
        props = {};
    }

    if (options.serializers) {
        props.serializers = options.serializers;
    }

    var headersToCopy = options.headers || [];

    return function bunyan(req, res, next) {
        if (!req.log && !options.log) {
            next();
            return;
        }

        var log = req.log || options.log;

        props.req_id = req.getId();
        headersToCopy.forEach(function (k) {

            if (req.headers[k]) {
                props[k] = req.headers[k];
            }
        });
        req.log = log.child(props, props.serializers ? false : true);

        if (props.req_id) {
            delete props.req_id;
        }

        next();
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.router"></a>[function <span class="apidocSignatureSpan">restify.</span>router (options)](#apidoc.element.restify.router)
- description and source-code
```javascript
function Router(options) {
    assert.object(options, 'options');
    assert.object(options.log, 'options.log');

    EventEmitter.call(this);

    this.cache = LRU({max: 100});
    this.contentType = options.contentType || [];

    if (!Array.isArray(this.contentType)) {
        this.contentType = [this.contentType];
    }
    assert.arrayOfString(this.contentType, 'options.contentType');

    this.log = options.log;
    this.mounts = {};
    this.name = 'RestifyRouter';

    // A list of methods to routes
    this.routes = {
        DELETE: [],
        GET: [],
        HEAD: [],
        OPTIONS: [],
        PATCH: [],
        POST: [],
        PUT: []
    };

    // So we can retrun 405 vs 404, we maintain a reverse mapping of URLs
    // to method
    this.reverse = {};

    this.versions = options.versions || options.version || [];

    if (!Array.isArray(this.versions)) {
        this.versions = [this.versions];
    }
    assert.arrayOfString(this.versions, 'options.versions');

    this.versions.forEach(function (v) {
        if (semver.valid(v)) {
            return (true);
        }

        throw new InvalidArgumentError('%s is not a valid semver', v);
    });
    this.versions.sort();

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.sanitizePath"></a>[function <span class="apidocSignatureSpan">restify.</span>sanitizePath (options)](#apidoc.element.restify.sanitizePath)
- description and source-code
```javascript
function sanitizePath(options) {
    options = options || {};

    function _sanitizePath(req, res, next) {
        req.url = strip(req.url);
        next();
    }

    return (_sanitizePath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.serveStatic"></a>[function <span class="apidocSignatureSpan">restify.</span>serveStatic (opts)](#apidoc.element.restify.serveStatic)
- description and source-code
```javascript
function serveStatic(opts) {
    opts = opts || {};
    assert.object(opts, 'options');
    assert.string(opts.directory, 'options.directory');
    assert.optionalNumber(opts.maxAge, 'options.maxAge');
    assert.optionalObject(opts.match, 'options.match');
    assert.optionalString(opts.charSet, 'options.charSet');
    assert.optionalString(opts.file, 'options.file');

    var p = path.normalize(opts.directory).replace(/\\/g, '/');
    var re = new RegExp('^' + escapeRE(p) + '/?.*');

    function serveFileFromStats(file, err, stats, isGzip, req, res, next) {
        if (err) {
            next(new ResourceNotFoundError(err,
                req.path()));
            return;
        } else if (!stats.isFile()) {
            next(new ResourceNotFoundError('%s does not exist', req.path()));
            return;
        }

        if (res.handledGzip && isGzip) {
            res.handledGzip();
        }

        var fstream = fs.createReadStream(file + (isGzip ? '.gz' : ''));
        var maxAge = opts.maxAge === undefined ? 3600 : opts.maxAge;
        fstream.once('open', function (fd) {
            res.cache({maxAge: maxAge});
            res.set('Content-Length', stats.size);
            res.set('Content-Type', mime.lookup(file));
            res.set('Last-Modified', stats.mtime);

            if (opts.charSet) {
                var type = res.getHeader('Content-Type') +
                    '; charset=' + opts.charSet;
                res.setHeader('Content-Type', type);
            }

            if (opts.etag) {
                res.set('ETag', opts.etag(stats, opts));
            }
            res.writeHead(200);
            fstream.pipe(res);
            fstream.once('end', function () {
                next(false);
            });
        });
    }

    function serveNormal(file, req, res, next) {
        fs.stat(file, function (err, stats) {
            if (!err && stats.isDirectory() && opts.default) {
                // Serve an index.html page or similar
                file = path.join(file, opts.default);
                fs.stat(file, function (dirErr, dirStats) {
                    serveFileFromStats(file,
                        dirErr,
                        dirStats,
                        false,
                        req,
                        res,
                        next);
                });
            } else {
                serveFileFromStats(file,
                    err,
                    stats,
                    false,
                    req,
                    res,
                    next);
            }
        });
    }

    function serve(req, res, next) {
        var file;

        if (opts.file) {
            //serves a direct file
            file = path.join(opts.directory,
                decodeURIComponent(opts.file));
        } else {
            file = path.join(opts.directory,
                decodeURIComponent(req.path()));
        }

        if (req.method !== 'GET' && req.method !== 'HEAD') {
            next(new MethodNotAllowedError(req.method));
            return;
        }

        if (!re.test(file.replace(/\\/g, '/'))) {
            next(new NotAuthorizedError(req.path()));
            return;
        }

        if (opts.match && !opts.match.test(file)) {
            next(new NotAuthorizedError(req.path()));
            return;
        }

        if (opts.gzip && req.acceptsEncoding('gzip')) {
            fs.stat(file + '.gz', function (err, stats) {
                if (!err) {
                    res.setHeader('Content-Encoding', 'gzip');
                    serveFileFromStats(file,
                        err,
                        stats,
                        true,
                        req,
                        res,
                        next);
                } else {
                    serveNormal(file, req, res, next);
                }
            });
        } else {
            serveNormal(file, req, res, next);
        }

    }

    return (serve);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.server"></a>[function <span class="apidocSignatureSpan">restify.</span>server (options)](#apidoc.element.restify.server)
- description and source-code
```javascript
function Server(options) {
    assert.object(options, 'options');
    assert.object(options.log, 'options.log');
    assert.object(options.router, 'options.router');

    var self = this;

    EventEmitter.call(this);

    this.before = [];
    this.chain = [];
    this.log = options.log;
    this.name = options.name || 'restify';
    this.router = options.router;
    this.routes = {};
    this.secure = false;
    this.versions = options.versions || options.version || [];
    this.socketio = options.socketio || false;

    var fmt = mergeFormatters(options.formatters);
    this.acceptable = fmt.acceptable;
    this.formatters = fmt.formatters;

    if (options.hasOwnProperty('handleUncaughtExceptions')) {
        this.handleUncaughtExceptions = options.handleUncaughtExceptions;
    } else {
        this.handleUncaughtExceptions = true;
    }

    if (options.spdy) {
        this.spdy = true;
        this.server = spdy.createServer(options.spdy);
    } else if ((options.cert || options.certificate) && options.key) {
        this.ca = options.ca;
        this.certificate = options.certificate || options.cert;
        this.key = options.key;
        this.passphrase = options.passphrase || null;
        this.secure = true;

        this.server = https.createServer({
            ca: self.ca,
            cert: self.certificate,
            key: self.key,
            passphrase: self.passphrase,
            rejectUnauthorized: options.rejectUnauthorized,
            requestCert: options.requestCert,
            ciphers: options.ciphers
        });
    } else if (options.httpsServerOptions) {
        this.server = https.createServer(options.httpsServerOptions);
    } else {
        this.server = http.createServer();
    }

    this.router.on('mount', this.emit.bind(this, 'mount'));

    if (!options.handleUpgrades && PROXY_EVENTS.indexOf('upgrade') === -1) {
        PROXY_EVENTS.push('upgrade');
    }
    PROXY_EVENTS.forEach(function (e) {
        self.server.on(e, self.emit.bind(self, e));
    });

    // Now the things we can't blindly proxy
    this.server.on('checkContinue', function onCheckContinue(req, res) {
        if (self.listeners('checkContinue').length > 0) {
            self.emit('checkContinue', req, res);
            return;
        }

        if (!options.noWriteContinue) {
            res.writeContinue();
        }

        self._setupRequest(req, res);
        self._handle(req, res, true);
    });

    if (options.handleUpgrades) {
        this.server.on('upgrade', function onUpgrade(req, socket, head) {
            req._upgradeRequest = true;
            var res = upgrade.createResponse(req, socket, head);
            self._setupRequest(req, res);
            self._handle(req, res);
        });
    }

    this.server.on('request', function onRequest(req, res) {
        self.emit('request', req, res);

        if (options.socketio && (/^\/socket\.io.*/).test(req.url)) {
            return;
        }

        self._setupRequest(req, res);
        self._handle(req, res);
    });

    this.__defineGetter__('maxHeadersCount', function () {
        return (self.server.maxHeadersCount);
    });

    this.__defineSetter__('maxHeadersCount', function (c) {
        self.server.maxHeadersCount = c;
        return (c);
    });

    this.__defineGetter__('url', function () {
        if (self.socketPath) {
            return ('http://' + self.socketPath);
        }

        var addr = self.address();
        var str = '';

        if (self.spdy) {
            str += 'spdy://';
        } else if (self.secure) {
            str += 'https://';
        } else {
            str += 'http://';
        }

        if (addr) {
            str += addr.family === 'IPv6' ?
                '[' + addr.address + ']' : addr.address;
            str += ':';
            str += addr.port;
        } else {
            str += '169.254.0.1:0000';
        }

        return (str);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.throttle"></a>[function <span class="apidocSignatureSpan">restify.</span>throttle (options)](#apidoc.element.restify.throttle)
- description and source-code
```javascript
function throttle(options) {
    assert.object(options, 'options');
    assert.number(options.burst, 'options.burst');
    assert.number(options.rate, 'options.rate');

    if (!xor(options.ip, options.xff, options.username)) {
        throw new Error('(ip ^ username ^ xff)');
    }

    var table = options.tokensTable ||
        new TokenTable({size: options.maxKeys});

    function rateLimit(req, res, next) {
        var attr;
        var burst = options.burst;
        var rate = options.rate;

        if (options.ip) {
            attr = req.connection.remoteAddress;
        } else if (options.xff) {
            attr = req.headers['x-forwarded-for'];
        } else if (options.username) {
            attr = req.username;
        } else {
            req.log.warn({config: options},
                'Invalid throttle configuration');
            return (next());
        }

        // Before bothering with overrides, see if this request
        // even matches
        if (!attr) {
            return (next());
        }

        // Check the overrides
        if (options.overrides &&
            options.overrides[attr] &&
            options.overrides[attr].burst !== undefined &&
            options.overrides[attr].rate !== undefined) {

            burst = options.overrides[attr].burst;
            rate = options.overrides[attr].rate;
        }

        if (!rate || !burst) {
            return (next());
        }

        var bucket = table.get(attr);

        if (!bucket) {
            bucket = new TokenBucket({
                capacity: burst,
                fillRate: rate
            });
            table.put(attr, bucket);
        }

        req.log.trace('Throttle(%s): num_tokens= %d',
            attr, bucket.tokens);

        if (!bucket.consume(1)) {
            req.log.info({
                address: req.connection.remoteAddress || '?',
                method: req.method,
                url: req.url,
                user: req.username || '?'
            }, 'Throttling');

            var msg = sprintf(MESSAGE, rate);
            return (next(new TooManyRequestsError(msg)));
        }

        return (next());
    }

    return (rateLimit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.urlEncodedBodyParser"></a>[function <span class="apidocSignatureSpan">restify.</span>urlEncodedBodyParser (options)](#apidoc.element.restify.urlEncodedBodyParser)
- description and source-code
```javascript
function urlEncodedBodyParser(options) {
    options = options || {};
    assert.object(options, 'options');

    var override = options.overrideParams;

    function parseUrlEncodedBody(req, res, next) {
        if (req.getContentType() !== MIME_TYPE || !req.body) {
            next();
            return;
        }

        try {
            var params = querystring.parse(req.body);

            if (options.mapParams !== false) {
                var keys = Object.keys(params);
                keys.forEach(function (k) {
                    var p = req.params[k];

                    if (p && !override) {
                        return (false);
                    }

                    req.params[k] = params[k];
                    return (true);
                });
            } else {
                req._body = req.body;
                req.body = params;
            }
        } catch (e) {
            next(new errors.InvalidContentError(e.message));
            return;
        }

        req.log.trace('req.params now: %j', req.params);
        next();
    }

    var chain = [];

    if (!options.bodyReader) {
        chain.push(bodyReader(options));
    }
    chain.push(parseUrlEncodedBody);
    return (chain);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.BadDigestError"></a>[module restify.BadDigestError](#apidoc.module.restify.BadDigestError)

#### <a name="apidoc.element.restify.BadDigestError.BadDigestError"></a>[function <span class="apidocSignatureSpan">restify.</span>BadDigestError (cause, message)](#apidoc.element.restify.BadDigestError.BadDigestError)
- description and source-code
```javascript
BadDigestError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.BadDigestError.super_"></a>[function <span class="apidocSignatureSpan">restify.BadDigestError.</span>super_ (options)](#apidoc.element.restify.BadDigestError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.BadGatewayError"></a>[module restify.BadGatewayError](#apidoc.module.restify.BadGatewayError)

#### <a name="apidoc.element.restify.BadGatewayError.BadGatewayError"></a>[function <span class="apidocSignatureSpan">restify.</span>BadGatewayError (cause, message)](#apidoc.element.restify.BadGatewayError.BadGatewayError)
- description and source-code
```javascript
BadGatewayError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.BadGatewayError.super_"></a>[function <span class="apidocSignatureSpan">restify.BadGatewayError.</span>super_ (options)](#apidoc.element.restify.BadGatewayError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.BadMethodError"></a>[module restify.BadMethodError](#apidoc.module.restify.BadMethodError)

#### <a name="apidoc.element.restify.BadMethodError.BadMethodError"></a>[function <span class="apidocSignatureSpan">restify.</span>BadMethodError (cause, message)](#apidoc.element.restify.BadMethodError.BadMethodError)
- description and source-code
```javascript
BadMethodError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.BadMethodError.super_"></a>[function <span class="apidocSignatureSpan">restify.BadMethodError.</span>super_ (options)](#apidoc.element.restify.BadMethodError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.BadRequestError"></a>[module restify.BadRequestError](#apidoc.module.restify.BadRequestError)

#### <a name="apidoc.element.restify.BadRequestError.BadRequestError"></a>[function <span class="apidocSignatureSpan">restify.</span>BadRequestError (cause, message)](#apidoc.element.restify.BadRequestError.BadRequestError)
- description and source-code
```javascript
BadRequestError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.BadRequestError.super_"></a>[function <span class="apidocSignatureSpan">restify.BadRequestError.</span>super_ (options)](#apidoc.element.restify.BadRequestError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.BandwidthLimitExceededError"></a>[module restify.BandwidthLimitExceededError](#apidoc.module.restify.BandwidthLimitExceededError)

#### <a name="apidoc.element.restify.BandwidthLimitExceededError.BandwidthLimitExceededError"></a>[function <span class="apidocSignatureSpan">restify.</span>BandwidthLimitExceededError (cause, message)](#apidoc.element.restify.BandwidthLimitExceededError.BandwidthLimitExceededError)
- description and source-code
```javascript
BandwidthLimitExceededError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.BandwidthLimitExceededError.super_"></a>[function <span class="apidocSignatureSpan">restify.BandwidthLimitExceededError.</span>super_ (options)](#apidoc.element.restify.BandwidthLimitExceededError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.CORS"></a>[module restify.CORS](#apidoc.module.restify.CORS)

#### <a name="apidoc.element.restify.CORS.CORS"></a>[function <span class="apidocSignatureSpan">restify.</span>CORS (opts)](#apidoc.element.restify.CORS.CORS)
- description and source-code
```javascript
function cors(opts) {
    assert.optionalObject(opts, 'options');
    opts = opts || {};
    assert.optionalArrayOfString(opts.origins, 'options.origins');
    assert.optionalBool(opts.credentials, 'options.credentials');
    assert.optionalArrayOfString(opts.headers, 'options.headers');

    cors.credentials = opts.credentials;
    cors.origins = opts.origins || ['*'];

    var headers = (opts.headers || []).slice(0);
    var origins = opts.origins || ['*'];

    EXPOSE_HEADERS.forEach(function (h) {
        if (headers.indexOf(h) === -1) {
            headers.push(h);
        }
    });

    // Handler for simple requests
    function restifyCORSSimple(req, res, next) {
        var origin;

        if (!(origin = matchOrigin(req, origins))) {
            next();
            return;
        }

        function corsOnHeader() {
            origin = req.headers.origin;

            if (opts.credentials) {
                res.setHeader(AC_ALLOW_ORIGIN, origin);
                res.setHeader(AC_ALLOW_CREDS, 'true');
            } else {
                res.setHeader(AC_ALLOW_ORIGIN, origin);
            }

            res.setHeader(AC_EXPOSE_HEADERS, headers.join(', '));
        }

        res.once('header', corsOnHeader);
        next();
    }

    return (restifyCORSSimple);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.CORS.matchOrigin"></a>[function <span class="apidocSignatureSpan">restify.CORS.</span>matchOrigin (req, origins)](#apidoc.element.restify.CORS.matchOrigin)
- description and source-code
```javascript
function matchOrigin(req, origins) {
    var origin = req.headers.origin;

    function belongs(o) {
        if (origin === o || o === '*') {
            origin = o;
            return (true);
        }

        return (false);
    }

    return ((origin && origins.some(belongs)) ? origin : false);
}
```
- example usage
```shell
...

if (!ok) {
    return (false);
}

// Verify the incoming origin against the whitelist. Pass the origin
// through if there is a match.
if (cors.matchOrigin(req, cors.origins)) {
    res.setHeader('Access-Control-Allow-Origin', origin);

    if (cors.credentials) {
        res.setHeader('Access-Control-Allow-Credentials', 'true');
    }
} else {
    res.setHeader('Access-Control-Allow-Origin', '*');
...
```



# <a name="apidoc.module.restify.ConflictError"></a>[module restify.ConflictError](#apidoc.module.restify.ConflictError)

#### <a name="apidoc.element.restify.ConflictError.ConflictError"></a>[function <span class="apidocSignatureSpan">restify.</span>ConflictError (cause, message)](#apidoc.element.restify.ConflictError.ConflictError)
- description and source-code
```javascript
ConflictError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ConflictError.super_"></a>[function <span class="apidocSignatureSpan">restify.ConflictError.</span>super_ (options)](#apidoc.element.restify.ConflictError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.ExpectationFailedError"></a>[module restify.ExpectationFailedError](#apidoc.module.restify.ExpectationFailedError)

#### <a name="apidoc.element.restify.ExpectationFailedError.ExpectationFailedError"></a>[function <span class="apidocSignatureSpan">restify.</span>ExpectationFailedError (cause, message)](#apidoc.element.restify.ExpectationFailedError.ExpectationFailedError)
- description and source-code
```javascript
ExpectationFailedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ExpectationFailedError.super_"></a>[function <span class="apidocSignatureSpan">restify.ExpectationFailedError.</span>super_ (options)](#apidoc.element.restify.ExpectationFailedError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.FailedDependencyError"></a>[module restify.FailedDependencyError](#apidoc.module.restify.FailedDependencyError)

#### <a name="apidoc.element.restify.FailedDependencyError.FailedDependencyError"></a>[function <span class="apidocSignatureSpan">restify.</span>FailedDependencyError (cause, message)](#apidoc.element.restify.FailedDependencyError.FailedDependencyError)
- description and source-code
```javascript
FailedDependencyError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.FailedDependencyError.super_"></a>[function <span class="apidocSignatureSpan">restify.FailedDependencyError.</span>super_ (options)](#apidoc.element.restify.FailedDependencyError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.ForbiddenError"></a>[module restify.ForbiddenError](#apidoc.module.restify.ForbiddenError)

#### <a name="apidoc.element.restify.ForbiddenError.ForbiddenError"></a>[function <span class="apidocSignatureSpan">restify.</span>ForbiddenError (cause, message)](#apidoc.element.restify.ForbiddenError.ForbiddenError)
- description and source-code
```javascript
ForbiddenError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ForbiddenError.super_"></a>[function <span class="apidocSignatureSpan">restify.ForbiddenError.</span>super_ (options)](#apidoc.element.restify.ForbiddenError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.GatewayTimeoutError"></a>[module restify.GatewayTimeoutError](#apidoc.module.restify.GatewayTimeoutError)

#### <a name="apidoc.element.restify.GatewayTimeoutError.GatewayTimeoutError"></a>[function <span class="apidocSignatureSpan">restify.</span>GatewayTimeoutError (cause, message)](#apidoc.element.restify.GatewayTimeoutError.GatewayTimeoutError)
- description and source-code
```javascript
GatewayTimeoutError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.GatewayTimeoutError.super_"></a>[function <span class="apidocSignatureSpan">restify.GatewayTimeoutError.</span>super_ (options)](#apidoc.element.restify.GatewayTimeoutError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.GoneError"></a>[module restify.GoneError](#apidoc.module.restify.GoneError)

#### <a name="apidoc.element.restify.GoneError.GoneError"></a>[function <span class="apidocSignatureSpan">restify.</span>GoneError (cause, message)](#apidoc.element.restify.GoneError.GoneError)
- description and source-code
```javascript
GoneError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.GoneError.super_"></a>[function <span class="apidocSignatureSpan">restify.GoneError.</span>super_ (options)](#apidoc.element.restify.GoneError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.HttpClient"></a>[module restify.HttpClient](#apidoc.module.restify.HttpClient)

#### <a name="apidoc.element.restify.HttpClient.HttpClient"></a>[function <span class="apidocSignatureSpan">restify.</span>HttpClient (options)](#apidoc.element.restify.HttpClient.HttpClient)
- description and source-code
```javascript
function HttpClient(options) {
    assert.object(options, 'options');
    assert.optionalObject(options.headers, 'options.headers');
    assert.object(options.log, 'options.log');
    assert.optionalFunc(options.signRequest, 'options.signRequest');
    assert.optionalString(options.socketPath, 'options.socketPath');
    assert.optionalString(options.url, 'options.url');

    EventEmitter.call(this);

    var self = this;

    this.agent = options.agent;
    this.ca = options.ca;
    this.cert = options.cert;
    this.ciphers = options.ciphers;
    this.connectTimeout = options.connectTimeout || false;
    this.requestTimeout = options.requestTimeout || false;
    this.headers = options.headers || {};
    this.log = options.log;

    if (!this.log.serializers) {
        // Ensure logger has a reasonable serializer for 'client_res'
        // and 'client_req' logged in this module.
        this.log = this.log.child({serializers: bunyan.serializers});
    }
    this.key = options.key;
    this.name = options.name || 'HttpClient';
    this.passphrase = options.passphrase;
    this.pfx = options.pfx;

    if (options.rejectUnauthorized !== undefined) {
        this.rejectUnauthorized = options.rejectUnauthorized;
    } else {
        this.rejectUnauthorized = true;
    }

    this.retry = cloneRetryOptions(options.retry);
    this.signRequest = options.signRequest || false;
    this.socketPath = options.socketPath || false;
    this.url = options.url ? url.parse(options.url) : {};

    if (process.env.https_proxy) {
        this.proxy = url.parse(process.env.https_proxy);
    } else if (process.env.http_proxy) {
        this.proxy = url.parse(process.env.http_proxy);
    } else if (options.proxy) {
        this.proxy = options.proxy;
    } else {
        this.proxy = false;
    }

    if (this.proxy && !isProxyForURL(self.url)) {
        this.proxy = false;
    }

    if (options.accept) {
        if (options.accept.indexOf('/') === -1) {
            options.accept = mime.lookup(options.accept);
        }

        this.headers.accept = options.accept;
    }

    if (options.contentType) {
        if (options.contentType.indexOf('/') === -1) {
            options.type = mime.lookup(options.contentType);
        }

        this.headers['content-type'] = options.contentType;
    }

    if (options.userAgent !== false) {
        this.headers['user-agent'] = options.userAgent ||
            defaultUserAgent();
    }

    if (options.version) {
        this.headers['accept-version'] = options.version;
    }

    if (this.agent === undefined) {
        var Agent;
        var maxSockets;

        if (this.proxy) {
            if (this.url.protocol === 'https:') {
                if (this.proxy.protocol === 'https:') {
                    Agent = tunnelAgent.httpsOverHttps;
                } else {
                    Agent = tunnelAgent.httpsOverHttp;
                }
            } else {
                if (this.proxy.protocol === 'https:') {
                    Agent = tunnelAgent.httpOverHttps;
                } else {
                    Agent = tunnelAgent.httpOverHttp;
                }
            }
        } else if (this.url.protocol === 'https:') {
            Agent = KeepAliveAgentSecure;
            maxSockets = httpsMaxSockets;
        } else {
            Agent = KeepAliveAgent;
            maxSockets = httpMaxSockets;
        }

        if (this.proxy) {
            this.agent = new Agent({
                proxy: self.proxy,
                rejectUnauthorized: self.rejectUnauthorized,
                ca: self.ca
            });
        } else {
            this.agent = new Agent({
                cert: self.cert,
                ca: self.ca,
                ciphers: self.ciphers,
                key: self.key,
                maxSockets: maxSockets,

                // require('keep-alive-agent')
                maxKeepAliveRequests: 0,
                maxKeepAliveTime: 0,

                // native keepalive
                keepAliveMsecs: 1000,
                keepAlive: true,

                passphrase: self.passp ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient.super_"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.</span>super_ ()](#apidoc.element.restify.HttpClient.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.HttpClient.prototype"></a>[module restify.HttpClient.prototype](#apidoc.module.restify.HttpClient.prototype)

#### <a name="apidoc.element.restify.HttpClient.prototype._options"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>_options (method, options)](#apidoc.element.restify.HttpClient.prototype._options)
- description and source-code
```javascript
_options = function (method, options) {
    if (typeof (options) !== 'object') {
        options = { path: options };
    }

    var self = this;
    var opts = {
        agent: options.agent !== undefined ? options.agent : self.agent,
        ca: options.ca || self.ca,
        cert: options.cert || self.cert,
        ciphers: options.ciphers || self.ciphers,
        connectTimeout: options.connectTimeout || self.connectTimeout,
        requestTimeout: options.requestTimeout || self.requestTimeout,
        headers: options.headers || {},
        key: options.key || self.key,
        log: options.log || self.log,
        method: method,
        passphrase: options.passphrase || self.passphrase,
        path: options.path || self.path,
        pfx: options.pfx || self.pfx,
        rejectUnauthorized: options.rejectUnauthorized ||
            self.rejectUnauthorized,
        retry: options.retry !== false ? options.retry : false,
        signRequest: options.signRequest || self.signRequest
    };

    if (!opts.retry && opts.retry !== false) {
        opts.retry = self.retry;
    }


    // Backwards compatibility with restify < 1.0
    if (options.query &&
        Object.keys(options.query).length &&
        opts.path.indexOf('?') === -1) {
        opts.path += '?' + querystring.stringify(options.query);
    }

    if (this.socketPath) {
        opts.socketPath = this.socketPath;
    }

    Object.keys(this.url).forEach(function (k) {
        if (!opts[k]) {
            opts[k] = self.url[k];
        }
    });

    Object.keys(self.headers).forEach(function (k) {
        if (!opts.headers[k]) {
            opts.headers[k] = self.headers[k];
        }
    });

    if (!opts.headers.date) {
        opts.headers.date = new Date().toUTCString();
    }

    if (method === 'GET' || method === 'HEAD' || method === 'DELETE') {
        if (opts.headers['content-type']) {
            delete opts.headers['content-type'];
        }

        if (opts.headers['content-md5']) {
            delete opts.headers['content-md5'];
        }

        if (opts.headers['content-length'] && method !== 'DELETE') {
            delete opts.headers['content-length'];
        }

        if (opts.headers['transfer-encoding']) {
            delete opts.headers['transfer-encoding'];
        }
    }

    return (opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient.prototype.basicAuth"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>basicAuth (username, password)](#apidoc.element.restify.HttpClient.prototype.basicAuth)
- description and source-code
```javascript
function basicAuth(username, password) {
    if (username === false) {
        delete this.headers.authorization;
    } else {
        assert.string(username, 'username');
        assert.string(password, 'password');

        var buffer = new Buffer(username + ':' + password, 'utf8');
        this.headers.authorization = 'Basic ' +
            buffer.toString('base64');
    }

    return (this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient.prototype.close"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>close ()](#apidoc.element.restify.HttpClient.prototype.close)
- description and source-code
```javascript
function close() {
    var sockets = this.agent.sockets;
    Object.keys((sockets || {})).forEach(function (k) {
        if (Array.isArray(sockets[k])) {
            sockets[k].forEach(function (s) {
                s.end();
            });
        }
    });

    sockets = this.agent.idleSockets || this.agent.freeSockets;
    Object.keys((sockets || {})).forEach(function (k) {
        sockets[k].forEach(function (s) {
            s.end();
        });
    });
}
```
- example usage
```shell
...
       assert.func(callback, 'callback');
   }

   this.server.once('close', function onClose() {
       return (callback ? callback() : false);
   });

   return (this.server.close());
};


// Register all the routing methods
/**
* Mounts a chain on the given path against this HTTP verb
*
...
```

#### <a name="apidoc.element.restify.HttpClient.prototype.del"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>del (options, callback)](#apidoc.element.restify.HttpClient.prototype.del)
- description and source-code
```javascript
function del(options, callback) {
    var opts = this._options('DELETE', options);

    return (this.read(opts, callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient.prototype.get"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>get (options, callback)](#apidoc.element.restify.HttpClient.prototype.get)
- description and source-code
```javascript
function get(options, callback) {
    var opts = this._options('GET', options);

    return (this.read(opts, callback));
}
```
- example usage
```shell
...
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});

server.listen(8080, function () {
  console.log('%s listening at %s', server.name, server.url);
});
...
```

#### <a name="apidoc.element.restify.HttpClient.prototype.head"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>head (options, callback)](#apidoc.element.restify.HttpClient.prototype.head)
- description and source-code
```javascript
function head(options, callback) {
    var opts = this._options('HEAD', options);

    return (this.read(opts, callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient.prototype.opts"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>opts (options, callback)](#apidoc.element.restify.HttpClient.prototype.opts)
- description and source-code
```javascript
function http_options(options, callback) {
    var _opts = this._options('OPTIONS', options);

    return (this.read(_opts, callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient.prototype.patch"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>patch (options, callback)](#apidoc.element.restify.HttpClient.prototype.patch)
- description and source-code
```javascript
function patch(options, callback) {
    var opts = this._options('PATCH', options);


    return (this.request(opts, callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient.prototype.post"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>post (options, callback)](#apidoc.element.restify.HttpClient.prototype.post)
- description and source-code
```javascript
function post(options, callback) {
    var opts = this._options('POST', options);

    return (this.request(opts, callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient.prototype.put"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>put (options, callback)](#apidoc.element.restify.HttpClient.prototype.put)
- description and source-code
```javascript
function put(options, callback) {
    var opts = this._options('PUT', options);

    return (this.request(opts, callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient.prototype.read"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>read (options, callback)](#apidoc.element.restify.HttpClient.prototype.read)
- description and source-code
```javascript
function read(options, callback) {
    var r = this.request(options, function readRequestCallback(err, req) {
        if (!err) {
            req.end();
        }

        return (callback(err, req));
    });
    return (r);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpClient.prototype.request"></a>[function <span class="apidocSignatureSpan">restify.HttpClient.prototype.</span>request (opts, cb)](#apidoc.element.restify.HttpClient.prototype.request)
- description and source-code
```javascript
function request(opts, cb) {
    assert.object(opts, 'options');
    assert.func(cb, 'callback');

    cb = once(cb);

    if (opts.retry === false) {
        rawRequest(opts, cb);
        return;
    }

    var call;
    var retry = cloneRetryOptions(opts.retry);

    opts._keep_alive = this._keep_alive;
    call = backoff.call(rawRequest, opts, cb);
    call.setStrategy(new backoff.ExponentialStrategy({
        initialDelay: retry.minTimeout,
        maxDelay: retry.maxTimeout
    }));
    call.failAfter(retry.retries);
    call.on('backoff', this.emit.bind(this, 'attempt'));

    call.start();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.HttpError"></a>[module restify.HttpError](#apidoc.module.restify.HttpError)

#### <a name="apidoc.element.restify.HttpError.HttpError"></a>[function <span class="apidocSignatureSpan">restify.</span>HttpError (options)](#apidoc.element.restify.HttpError.HttpError)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpError.super_"></a>[function <span class="apidocSignatureSpan">restify.HttpError.</span>super_ ()](#apidoc.element.restify.HttpError.super_)
- description and source-code
```javascript
function WError()
{
	var args, obj, parsed, options;

	args = Array.prototype.slice.call(arguments, 0);
	if (!(this instanceof WError)) {
		obj = Object.create(WError.prototype);
		WError.apply(obj, args);
		return (obj);
	}

	parsed = parseConstructorArguments({
	    'argv': args,
	    'strict': false
	});

	options = parsed.options;
	options['skipCauseMessage'] = true;
	VError.call(this, options, '%s', parsed.shortmessage);

	return (this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.HttpError.super_"></a>[module restify.HttpError.super_](#apidoc.module.restify.HttpError.super_)

#### <a name="apidoc.element.restify.HttpError.super_.super_"></a>[function <span class="apidocSignatureSpan">restify.HttpError.</span>super_ ()](#apidoc.element.restify.HttpError.super_.super_)
- description and source-code
```javascript
function VError()
{
	var args, obj, parsed, cause, ctor, message, k;

	args = Array.prototype.slice.call(arguments, 0);

	<span class="apidocCodeCommentSpan">/*
	 * This is a regrettable pattern, but JavaScript's built-in Error class
	 * is defined to work this way, so we allow the constructor to be called
	 * without "new".
	 */
</span>	if (!(this instanceof VError)) {
		obj = Object.create(VError.prototype);
		VError.apply(obj, arguments);
		return (obj);
	}

	/*
	 * For convenience and backwards compatibility, we support several
	 * different calling forms.  Normalize them here.
	 */
	parsed = parseConstructorArguments({
	    'argv': args,
	    'strict': false
	});

	/*
	 * If we've been given a name, apply it now.
	 */
	if (parsed.options.name) {
		mod_assertplus.string(parsed.options.name,
		    'error\'s "name" must be a string');
		this.name = parsed.options.name;
	}

	/*
	 * For debugging, we keep track of the original short message (attached
	 * this Error particularly) separately from the complete message (which
	 * includes the messages of our cause chain).
	 */
	this.jse_shortmsg = parsed.shortmessage;
	message = parsed.shortmessage;

	/*
	 * If we've been given a cause, record a reference to it and update our
	 * message appropriately.
	 */
	cause = parsed.options.cause;
	if (cause) {
		mod_assertplus.ok(mod_isError(cause), 'cause is not an Error');
		this.jse_cause = cause;

		if (!parsed.options.skipCauseMessage) {
			message += ': ' + cause.message;
		}
	}

	/*
	 * If we've been given an object with properties, shallow-copy that
	 * here.  We don't want to use a deep copy in case there are non-plain
	 * objects here, but we don't want to use the original object in case
	 * the caller modifies it later.
	 */
	this.jse_info = {};
	if (parsed.options.info) {
		for (k in parsed.options.info) {
			this.jse_info[k] = parsed.options.info[k];
		}
	}

	this.message = message;
	Error.call(this, message);

	if (Error.captureStackTrace) {
		ctor = parsed.options.constructorOpt || this.constructor;
		Error.captureStackTrace(this, ctor);
	}

	return (this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.HttpError.super_.prototype"></a>[module restify.HttpError.super_.prototype](#apidoc.module.restify.HttpError.super_.prototype)

#### <a name="apidoc.element.restify.HttpError.super_.prototype.cause"></a>[function <span class="apidocSignatureSpan">restify.HttpError.super_.prototype.</span>cause (c)](#apidoc.element.restify.HttpError.super_.prototype.cause)
- description and source-code
```javascript
function we_cause(c)
{
	if (mod_isError(c))
		this.jse_cause = c;

	return (this.jse_cause);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpError.super_.prototype.toString"></a>[function <span class="apidocSignatureSpan">restify.HttpError.super_.prototype.</span>toString ()](#apidoc.element.restify.HttpError.super_.prototype.toString)
- description and source-code
```javascript
function we_toString()
{
	var str = (this.hasOwnProperty('name') && this.name ||
		this.constructor.name || this.constructor.prototype.name);
	if (this.message)
		str += ': ' + this.message;
	if (this.jse_cause && this.jse_cause.message)
		str += '; caused by ' + this.jse_cause.toString();

	return (str);
}
```
- example usage
```shell
...
    // Client probes
    // method, url, headers, id
    'client-request': ['char *', 'char *', 'json', 'int'],

    // id, statusCode, headers
    'client-response': ['int', 'int', 'json'],

    // id, Error.toString()
    'client-error': ['id', 'char *']
};
var PROVIDER;


///--- API
...
```



# <a name="apidoc.module.restify.HttpError.super_.super_.prototype"></a>[module restify.HttpError.super_.super_.prototype](#apidoc.module.restify.HttpError.super_.super_.prototype)

#### <a name="apidoc.element.restify.HttpError.super_.super_.prototype.cause"></a>[function <span class="apidocSignatureSpan">restify.HttpError.super_.super_.prototype.</span>cause ()](#apidoc.element.restify.HttpError.super_.super_.prototype.cause)
- description and source-code
```javascript
function ve_cause()
{
	var cause = VError.cause(this);
	return (cause === null ? undefined : cause);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpError.super_.super_.prototype.toString"></a>[function <span class="apidocSignatureSpan">restify.HttpError.super_.super_.prototype.</span>toString ()](#apidoc.element.restify.HttpError.super_.super_.prototype.toString)
- description and source-code
```javascript
function ve_toString()
{
	var str = (this.hasOwnProperty('name') && this.name ||
		this.constructor.name || this.constructor.prototype.name);
	if (this.message)
		str += ': ' + this.message;

	return (str);
}
```
- example usage
```shell
...
    // Client probes
    // method, url, headers, id
    'client-request': ['char *', 'char *', 'json', 'int'],

    // id, statusCode, headers
    'client-response': ['int', 'int', 'json'],

    // id, Error.toString()
    'client-error': ['id', 'char *']
};
var PROVIDER;


///--- API
...
```



# <a name="apidoc.module.restify.HttpVersionNotSupportedError"></a>[module restify.HttpVersionNotSupportedError](#apidoc.module.restify.HttpVersionNotSupportedError)

#### <a name="apidoc.element.restify.HttpVersionNotSupportedError.HttpVersionNotSupportedError"></a>[function <span class="apidocSignatureSpan">restify.</span>HttpVersionNotSupportedError (cause, message)](#apidoc.element.restify.HttpVersionNotSupportedError.HttpVersionNotSupportedError)
- description and source-code
```javascript
HttpVersionNotSupportedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.HttpVersionNotSupportedError.super_"></a>[function <span class="apidocSignatureSpan">restify.HttpVersionNotSupportedError.</span>super_ (options)](#apidoc.element.restify.HttpVersionNotSupportedError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.ImATeapotError"></a>[module restify.ImATeapotError](#apidoc.module.restify.ImATeapotError)

#### <a name="apidoc.element.restify.ImATeapotError.ImATeapotError"></a>[function <span class="apidocSignatureSpan">restify.</span>ImATeapotError (cause, message)](#apidoc.element.restify.ImATeapotError.ImATeapotError)
- description and source-code
```javascript
ImATeapotError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ImATeapotError.super_"></a>[function <span class="apidocSignatureSpan">restify.ImATeapotError.</span>super_ (options)](#apidoc.element.restify.ImATeapotError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.InsufficientStorageError"></a>[module restify.InsufficientStorageError](#apidoc.module.restify.InsufficientStorageError)

#### <a name="apidoc.element.restify.InsufficientStorageError.InsufficientStorageError"></a>[function <span class="apidocSignatureSpan">restify.</span>InsufficientStorageError (cause, message)](#apidoc.element.restify.InsufficientStorageError.InsufficientStorageError)
- description and source-code
```javascript
InsufficientStorageError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InsufficientStorageError.super_"></a>[function <span class="apidocSignatureSpan">restify.InsufficientStorageError.</span>super_ (options)](#apidoc.element.restify.InsufficientStorageError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.InternalError"></a>[module restify.InternalError](#apidoc.module.restify.InternalError)

#### <a name="apidoc.element.restify.InternalError.InternalError"></a>[function <span class="apidocSignatureSpan">restify.</span>InternalError (cause, message)](#apidoc.element.restify.InternalError.InternalError)
- description and source-code
```javascript
InternalError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
...
        emittedError = true;
    } else {
        res.send(arg);
    }
    done = true;
} else if (typeof (arg) === 'string') { // GH-193, allow redirect
    if (req._rstfy_chained_route) {
        var _e = new errors.InternalError();
        log.error({
            err: _e
        }, 'Multiple next("chain") calls not ' +
            'supported');
        res.send(_e);
        return (false);
    }
...
```

#### <a name="apidoc.element.restify.InternalError.super_"></a>[function <span class="apidocSignatureSpan">restify.InternalError.</span>super_ (options)](#apidoc.element.restify.InternalError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.InternalServerError"></a>[module restify.InternalServerError](#apidoc.module.restify.InternalServerError)

#### <a name="apidoc.element.restify.InternalServerError.InternalServerError"></a>[function <span class="apidocSignatureSpan">restify.</span>InternalServerError (cause, message)](#apidoc.element.restify.InternalServerError.InternalServerError)
- description and source-code
```javascript
InternalServerError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InternalServerError.super_"></a>[function <span class="apidocSignatureSpan">restify.InternalServerError.</span>super_ (options)](#apidoc.element.restify.InternalServerError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.InvalidArgumentError"></a>[module restify.InvalidArgumentError](#apidoc.module.restify.InvalidArgumentError)

#### <a name="apidoc.element.restify.InvalidArgumentError.InvalidArgumentError"></a>[function <span class="apidocSignatureSpan">restify.</span>InvalidArgumentError (cause, message)](#apidoc.element.restify.InvalidArgumentError.InvalidArgumentError)
- description and source-code
```javascript
InvalidArgumentError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InvalidArgumentError.super_"></a>[function <span class="apidocSignatureSpan">restify.InvalidArgumentError.</span>super_ (options)](#apidoc.element.restify.InvalidArgumentError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.InvalidContentError"></a>[module restify.InvalidContentError](#apidoc.module.restify.InvalidContentError)

#### <a name="apidoc.element.restify.InvalidContentError.InvalidContentError"></a>[function <span class="apidocSignatureSpan">restify.</span>InvalidContentError (cause, message)](#apidoc.element.restify.InvalidContentError.InvalidContentError)
- description and source-code
```javascript
InvalidContentError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InvalidContentError.super_"></a>[function <span class="apidocSignatureSpan">restify.InvalidContentError.</span>super_ (options)](#apidoc.element.restify.InvalidContentError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.InvalidCredentialsError"></a>[module restify.InvalidCredentialsError](#apidoc.module.restify.InvalidCredentialsError)

#### <a name="apidoc.element.restify.InvalidCredentialsError.InvalidCredentialsError"></a>[function <span class="apidocSignatureSpan">restify.</span>InvalidCredentialsError (cause, message)](#apidoc.element.restify.InvalidCredentialsError.InvalidCredentialsError)
- description and source-code
```javascript
InvalidCredentialsError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InvalidCredentialsError.super_"></a>[function <span class="apidocSignatureSpan">restify.InvalidCredentialsError.</span>super_ (options)](#apidoc.element.restify.InvalidCredentialsError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.InvalidHeaderError"></a>[module restify.InvalidHeaderError](#apidoc.module.restify.InvalidHeaderError)

#### <a name="apidoc.element.restify.InvalidHeaderError.InvalidHeaderError"></a>[function <span class="apidocSignatureSpan">restify.</span>InvalidHeaderError (cause, message)](#apidoc.element.restify.InvalidHeaderError.InvalidHeaderError)
- description and source-code
```javascript
InvalidHeaderError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InvalidHeaderError.super_"></a>[function <span class="apidocSignatureSpan">restify.InvalidHeaderError.</span>super_ (options)](#apidoc.element.restify.InvalidHeaderError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.InvalidVersionError"></a>[module restify.InvalidVersionError](#apidoc.module.restify.InvalidVersionError)

#### <a name="apidoc.element.restify.InvalidVersionError.InvalidVersionError"></a>[function <span class="apidocSignatureSpan">restify.</span>InvalidVersionError (cause, message)](#apidoc.element.restify.InvalidVersionError.InvalidVersionError)
- description and source-code
```javascript
InvalidVersionError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.InvalidVersionError.super_"></a>[function <span class="apidocSignatureSpan">restify.InvalidVersionError.</span>super_ (options)](#apidoc.element.restify.InvalidVersionError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.JsonClient"></a>[module restify.JsonClient](#apidoc.module.restify.JsonClient)

#### <a name="apidoc.element.restify.JsonClient.JsonClient"></a>[function <span class="apidocSignatureSpan">restify.</span>JsonClient (options)](#apidoc.element.restify.JsonClient.JsonClient)
- description and source-code
```javascript
function JsonClient(options) {
    assert.object(options, 'options');

    options.accept = 'application/json';
    options.name = options.name || 'JsonClient';
    options.contentType = 'application/json';

    StringClient.call(this, options);

    this._super = StringClient.prototype;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.JsonClient.super_"></a>[function <span class="apidocSignatureSpan">restify.JsonClient.</span>super_ (options)](#apidoc.element.restify.JsonClient.super_)
- description and source-code
```javascript
function StringClient(options) {
    assert.object(options, 'options');
    assert.optionalObject(options.gzip, 'options.gzip');

    options.accept = options.accept || 'text/plain';
    options.name = options.name || 'StringClient';
    options.contentType =
        options.contentType || 'application/x-www-form-urlencoded';

    HttpClient.call(this, options);
    this.gzip = options.gzip;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.JsonClient.prototype"></a>[module restify.JsonClient.prototype](#apidoc.module.restify.JsonClient.prototype)

#### <a name="apidoc.element.restify.JsonClient.prototype.parse"></a>[function <span class="apidocSignatureSpan">restify.JsonClient.prototype.</span>parse (req, callback)](#apidoc.element.restify.JsonClient.prototype.parse)
- description and source-code
```javascript
function parse(req, callback) {
    var log = this.log;

    function parseResponse(err, req2, res, data) {
        var obj;

        try {
            if (data && !/^\s*$/.test(data)) {
                obj = JSON.parse(data);
            }
        } catch (e) {
            // Not really sure what else we can do here, besides
            // make the client just keep going.
            log.trace(e, 'Invalid JSON in response');
        }
        obj = obj || {};

        if (res && res.statusCode >= 400) {
            // Upcast error to a RestError (if we can)
            // Be nice and handle errors like
            // { error: { code: '', message: '' } }
            // in addition to { code: '', message: '' }.
            if (obj.code || (obj.error && obj.error.code)) {
                var _c = obj.code ||
                    (obj.error ? obj.error.code : '') ||
                    '';
                var _m = obj.message ||
                    (obj.error ? obj.error.message : '') ||
                    '';

                err = new RestError({
                    message: _m,
                    restCode: _c,
                    statusCode: res.statusCode
                });
                err.name = err.restCode;

                if (!/Error$/.test(err.name)) {
                    err.name += 'Error';
                }
            } else if (!err) {
                err = codeToHttpError(res.statusCode,
                    obj.message || '', data);
            }
        }

        if (err) {
            err.body = obj;
        }

        callback((err || null), req2, res, obj);
    }

    return (this._super.parse.call(this, req, parseResponse));
}
```
- example usage
```shell
...
 * returns a parsed URL object.
 * @public
 * @function getUrl
 * @returns  {Object}
 */
Request.prototype.getUrl = function getUrl() {
    if (this._cacheURL !== this.url) {
        this._url = url.parse(this.url);
        this._cacheURL = this.url;
    }
    return (this._url);
};


/**
...
```

#### <a name="apidoc.element.restify.JsonClient.prototype.write"></a>[function <span class="apidocSignatureSpan">restify.JsonClient.prototype.</span>write (options, body, callback)](#apidoc.element.restify.JsonClient.prototype.write)
- description and source-code
```javascript
function write(options, body, callback) {
    assert.ok(body !== undefined, 'body');
    assert.object(body, 'body');

    body = JSON.stringify(body !== null ? body : {});
    return (this._super.write.call(this, options, body, callback));
}
```
- example usage
```shell
...
Object.keys(headers).forEach(function (k) {
    self.setHeader(k, headers[k]);
});

self.writeHead(self.statusCode);

if (self._data && !(isHead || code === 204 || code === 304)) {
    self.write(self._data);
}

self.end();

if (log.trace()) {
    log.trace({res: self}, 'response sent');
}
...
```



# <a name="apidoc.module.restify.LengthRequiredError"></a>[module restify.LengthRequiredError](#apidoc.module.restify.LengthRequiredError)

#### <a name="apidoc.element.restify.LengthRequiredError.LengthRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>LengthRequiredError (cause, message)](#apidoc.element.restify.LengthRequiredError.LengthRequiredError)
- description and source-code
```javascript
LengthRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.LengthRequiredError.super_"></a>[function <span class="apidocSignatureSpan">restify.LengthRequiredError.</span>super_ (options)](#apidoc.element.restify.LengthRequiredError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.LockedError"></a>[module restify.LockedError](#apidoc.module.restify.LockedError)

#### <a name="apidoc.element.restify.LockedError.LockedError"></a>[function <span class="apidocSignatureSpan">restify.</span>LockedError (cause, message)](#apidoc.element.restify.LockedError.LockedError)
- description and source-code
```javascript
LockedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.LockedError.super_"></a>[function <span class="apidocSignatureSpan">restify.LockedError.</span>super_ (options)](#apidoc.element.restify.LockedError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.LoopDetectedError"></a>[module restify.LoopDetectedError](#apidoc.module.restify.LoopDetectedError)

#### <a name="apidoc.element.restify.LoopDetectedError.LoopDetectedError"></a>[function <span class="apidocSignatureSpan">restify.</span>LoopDetectedError (cause, message)](#apidoc.element.restify.LoopDetectedError.LoopDetectedError)
- description and source-code
```javascript
LoopDetectedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.LoopDetectedError.super_"></a>[function <span class="apidocSignatureSpan">restify.LoopDetectedError.</span>super_ (options)](#apidoc.element.restify.LoopDetectedError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.MethodNotAllowedError"></a>[module restify.MethodNotAllowedError](#apidoc.module.restify.MethodNotAllowedError)

#### <a name="apidoc.element.restify.MethodNotAllowedError.MethodNotAllowedError"></a>[function <span class="apidocSignatureSpan">restify.</span>MethodNotAllowedError (cause, message)](#apidoc.element.restify.MethodNotAllowedError.MethodNotAllowedError)
- description and source-code
```javascript
MethodNotAllowedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.MethodNotAllowedError.super_"></a>[function <span class="apidocSignatureSpan">restify.MethodNotAllowedError.</span>super_ (options)](#apidoc.element.restify.MethodNotAllowedError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.MisdirectedRequestError"></a>[module restify.MisdirectedRequestError](#apidoc.module.restify.MisdirectedRequestError)

#### <a name="apidoc.element.restify.MisdirectedRequestError.MisdirectedRequestError"></a>[function <span class="apidocSignatureSpan">restify.</span>MisdirectedRequestError (cause, message)](#apidoc.element.restify.MisdirectedRequestError.MisdirectedRequestError)
- description and source-code
```javascript
MisdirectedRequestError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.MisdirectedRequestError.super_"></a>[function <span class="apidocSignatureSpan">restify.MisdirectedRequestError.</span>super_ (options)](#apidoc.element.restify.MisdirectedRequestError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.MissingParameterError"></a>[module restify.MissingParameterError](#apidoc.module.restify.MissingParameterError)

#### <a name="apidoc.element.restify.MissingParameterError.MissingParameterError"></a>[function <span class="apidocSignatureSpan">restify.</span>MissingParameterError (cause, message)](#apidoc.element.restify.MissingParameterError.MissingParameterError)
- description and source-code
```javascript
MissingParameterError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.MissingParameterError.super_"></a>[function <span class="apidocSignatureSpan">restify.MissingParameterError.</span>super_ (options)](#apidoc.element.restify.MissingParameterError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.NetworkAuthenticationRequiredError"></a>[module restify.NetworkAuthenticationRequiredError](#apidoc.module.restify.NetworkAuthenticationRequiredError)

#### <a name="apidoc.element.restify.NetworkAuthenticationRequiredError.NetworkAuthenticationRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>NetworkAuthenticationRequiredError (cause, message)](#apidoc.element.restify.NetworkAuthenticationRequiredError.NetworkAuthenticationRequiredError)
- description and source-code
```javascript
NetworkAuthenticationRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NetworkAuthenticationRequiredError.super_"></a>[function <span class="apidocSignatureSpan">restify.NetworkAuthenticationRequiredError.</span>super_ (options)](#apidoc.element.restify.NetworkAuthenticationRequiredError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.NotAcceptableError"></a>[module restify.NotAcceptableError](#apidoc.module.restify.NotAcceptableError)

#### <a name="apidoc.element.restify.NotAcceptableError.NotAcceptableError"></a>[function <span class="apidocSignatureSpan">restify.</span>NotAcceptableError (cause, message)](#apidoc.element.restify.NotAcceptableError.NotAcceptableError)
- description and source-code
```javascript
NotAcceptableError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NotAcceptableError.super_"></a>[function <span class="apidocSignatureSpan">restify.NotAcceptableError.</span>super_ (options)](#apidoc.element.restify.NotAcceptableError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.NotAuthorizedError"></a>[module restify.NotAuthorizedError](#apidoc.module.restify.NotAuthorizedError)

#### <a name="apidoc.element.restify.NotAuthorizedError.NotAuthorizedError"></a>[function <span class="apidocSignatureSpan">restify.</span>NotAuthorizedError (cause, message)](#apidoc.element.restify.NotAuthorizedError.NotAuthorizedError)
- description and source-code
```javascript
NotAuthorizedError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NotAuthorizedError.super_"></a>[function <span class="apidocSignatureSpan">restify.NotAuthorizedError.</span>super_ (options)](#apidoc.element.restify.NotAuthorizedError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.NotExtendedError"></a>[module restify.NotExtendedError](#apidoc.module.restify.NotExtendedError)

#### <a name="apidoc.element.restify.NotExtendedError.NotExtendedError"></a>[function <span class="apidocSignatureSpan">restify.</span>NotExtendedError (cause, message)](#apidoc.element.restify.NotExtendedError.NotExtendedError)
- description and source-code
```javascript
NotExtendedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NotExtendedError.super_"></a>[function <span class="apidocSignatureSpan">restify.NotExtendedError.</span>super_ (options)](#apidoc.element.restify.NotExtendedError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.NotFoundError"></a>[module restify.NotFoundError](#apidoc.module.restify.NotFoundError)

#### <a name="apidoc.element.restify.NotFoundError.NotFoundError"></a>[function <span class="apidocSignatureSpan">restify.</span>NotFoundError (cause, message)](#apidoc.element.restify.NotFoundError.NotFoundError)
- description and source-code
```javascript
NotFoundError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NotFoundError.super_"></a>[function <span class="apidocSignatureSpan">restify.NotFoundError.</span>super_ (options)](#apidoc.element.restify.NotFoundError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.NotImplementedError"></a>[module restify.NotImplementedError](#apidoc.module.restify.NotImplementedError)

#### <a name="apidoc.element.restify.NotImplementedError.NotImplementedError"></a>[function <span class="apidocSignatureSpan">restify.</span>NotImplementedError (cause, message)](#apidoc.element.restify.NotImplementedError.NotImplementedError)
- description and source-code
```javascript
NotImplementedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.NotImplementedError.super_"></a>[function <span class="apidocSignatureSpan">restify.NotImplementedError.</span>super_ (options)](#apidoc.element.restify.NotImplementedError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.PayloadTooLargeError"></a>[module restify.PayloadTooLargeError](#apidoc.module.restify.PayloadTooLargeError)

#### <a name="apidoc.element.restify.PayloadTooLargeError.PayloadTooLargeError"></a>[function <span class="apidocSignatureSpan">restify.</span>PayloadTooLargeError (cause, message)](#apidoc.element.restify.PayloadTooLargeError.PayloadTooLargeError)
- description and source-code
```javascript
PayloadTooLargeError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.PayloadTooLargeError.super_"></a>[function <span class="apidocSignatureSpan">restify.PayloadTooLargeError.</span>super_ (options)](#apidoc.element.restify.PayloadTooLargeError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.PaymentRequiredError"></a>[module restify.PaymentRequiredError](#apidoc.module.restify.PaymentRequiredError)

#### <a name="apidoc.element.restify.PaymentRequiredError.PaymentRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>PaymentRequiredError (cause, message)](#apidoc.element.restify.PaymentRequiredError.PaymentRequiredError)
- description and source-code
```javascript
PaymentRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.PaymentRequiredError.super_"></a>[function <span class="apidocSignatureSpan">restify.PaymentRequiredError.</span>super_ (options)](#apidoc.element.restify.PaymentRequiredError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.PreconditionFailedError"></a>[module restify.PreconditionFailedError](#apidoc.module.restify.PreconditionFailedError)

#### <a name="apidoc.element.restify.PreconditionFailedError.PreconditionFailedError"></a>[function <span class="apidocSignatureSpan">restify.</span>PreconditionFailedError (cause, message)](#apidoc.element.restify.PreconditionFailedError.PreconditionFailedError)
- description and source-code
```javascript
PreconditionFailedError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.PreconditionFailedError.super_"></a>[function <span class="apidocSignatureSpan">restify.PreconditionFailedError.</span>super_ (options)](#apidoc.element.restify.PreconditionFailedError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.PreconditionRequiredError"></a>[module restify.PreconditionRequiredError](#apidoc.module.restify.PreconditionRequiredError)

#### <a name="apidoc.element.restify.PreconditionRequiredError.PreconditionRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>PreconditionRequiredError (cause, message)](#apidoc.element.restify.PreconditionRequiredError.PreconditionRequiredError)
- description and source-code
```javascript
PreconditionRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.PreconditionRequiredError.super_"></a>[function <span class="apidocSignatureSpan">restify.PreconditionRequiredError.</span>super_ (options)](#apidoc.element.restify.PreconditionRequiredError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.ProxyAuthenticationRequiredError"></a>[module restify.ProxyAuthenticationRequiredError](#apidoc.module.restify.ProxyAuthenticationRequiredError)

#### <a name="apidoc.element.restify.ProxyAuthenticationRequiredError.ProxyAuthenticationRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>ProxyAuthenticationRequiredError (cause, message)](#apidoc.element.restify.ProxyAuthenticationRequiredError.ProxyAuthenticationRequiredError)
- description and source-code
```javascript
ProxyAuthenticationRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ProxyAuthenticationRequiredError.super_"></a>[function <span class="apidocSignatureSpan">restify.ProxyAuthenticationRequiredError.</span>super_ (options)](#apidoc.element.restify.ProxyAuthenticationRequiredError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.RangeNotSatisfiableError"></a>[module restify.RangeNotSatisfiableError](#apidoc.module.restify.RangeNotSatisfiableError)

#### <a name="apidoc.element.restify.RangeNotSatisfiableError.RangeNotSatisfiableError"></a>[function <span class="apidocSignatureSpan">restify.</span>RangeNotSatisfiableError (cause, message)](#apidoc.element.restify.RangeNotSatisfiableError.RangeNotSatisfiableError)
- description and source-code
```javascript
RangeNotSatisfiableError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RangeNotSatisfiableError.super_"></a>[function <span class="apidocSignatureSpan">restify.RangeNotSatisfiableError.</span>super_ (options)](#apidoc.element.restify.RangeNotSatisfiableError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.RequestExpiredError"></a>[module restify.RequestExpiredError](#apidoc.module.restify.RequestExpiredError)

#### <a name="apidoc.element.restify.RequestExpiredError.RequestExpiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>RequestExpiredError (cause, message)](#apidoc.element.restify.RequestExpiredError.RequestExpiredError)
- description and source-code
```javascript
RequestExpiredError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RequestExpiredError.super_"></a>[function <span class="apidocSignatureSpan">restify.RequestExpiredError.</span>super_ (options)](#apidoc.element.restify.RequestExpiredError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.RequestHeaderFieldsTooLargeError"></a>[module restify.RequestHeaderFieldsTooLargeError](#apidoc.module.restify.RequestHeaderFieldsTooLargeError)

#### <a name="apidoc.element.restify.RequestHeaderFieldsTooLargeError.RequestHeaderFieldsTooLargeError"></a>[function <span class="apidocSignatureSpan">restify.</span>RequestHeaderFieldsTooLargeError (cause, message)](#apidoc.element.restify.RequestHeaderFieldsTooLargeError.RequestHeaderFieldsTooLargeError)
- description and source-code
```javascript
RequestHeaderFieldsTooLargeError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RequestHeaderFieldsTooLargeError.super_"></a>[function <span class="apidocSignatureSpan">restify.RequestHeaderFieldsTooLargeError.</span>super_ (options)](#apidoc.element.restify.RequestHeaderFieldsTooLargeError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.RequestThrottledError"></a>[module restify.RequestThrottledError](#apidoc.module.restify.RequestThrottledError)

#### <a name="apidoc.element.restify.RequestThrottledError.RequestThrottledError"></a>[function <span class="apidocSignatureSpan">restify.</span>RequestThrottledError (cause, message)](#apidoc.element.restify.RequestThrottledError.RequestThrottledError)
- description and source-code
```javascript
RequestThrottledError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RequestThrottledError.super_"></a>[function <span class="apidocSignatureSpan">restify.RequestThrottledError.</span>super_ (options)](#apidoc.element.restify.RequestThrottledError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.RequestTimeoutError"></a>[module restify.RequestTimeoutError](#apidoc.module.restify.RequestTimeoutError)

#### <a name="apidoc.element.restify.RequestTimeoutError.RequestTimeoutError"></a>[function <span class="apidocSignatureSpan">restify.</span>RequestTimeoutError (cause, message)](#apidoc.element.restify.RequestTimeoutError.RequestTimeoutError)
- description and source-code
```javascript
RequestTimeoutError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RequestTimeoutError.super_"></a>[function <span class="apidocSignatureSpan">restify.RequestTimeoutError.</span>super_ (options)](#apidoc.element.restify.RequestTimeoutError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.ResourceNotFoundError"></a>[module restify.ResourceNotFoundError](#apidoc.module.restify.ResourceNotFoundError)

#### <a name="apidoc.element.restify.ResourceNotFoundError.ResourceNotFoundError"></a>[function <span class="apidocSignatureSpan">restify.</span>ResourceNotFoundError (cause, message)](#apidoc.element.restify.ResourceNotFoundError.ResourceNotFoundError)
- description and source-code
```javascript
ResourceNotFoundError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ResourceNotFoundError.super_"></a>[function <span class="apidocSignatureSpan">restify.ResourceNotFoundError.</span>super_ (options)](#apidoc.element.restify.ResourceNotFoundError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.RestError"></a>[module restify.RestError](#apidoc.module.restify.RestError)

#### <a name="apidoc.element.restify.RestError.RestError"></a>[function <span class="apidocSignatureSpan">restify.</span>RestError (options)](#apidoc.element.restify.RestError.RestError)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.RestError.super_"></a>[function <span class="apidocSignatureSpan">restify.RestError.</span>super_ (options)](#apidoc.element.restify.RestError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.ServiceUnavailableError"></a>[module restify.ServiceUnavailableError](#apidoc.module.restify.ServiceUnavailableError)

#### <a name="apidoc.element.restify.ServiceUnavailableError.ServiceUnavailableError"></a>[function <span class="apidocSignatureSpan">restify.</span>ServiceUnavailableError (cause, message)](#apidoc.element.restify.ServiceUnavailableError.ServiceUnavailableError)
- description and source-code
```javascript
ServiceUnavailableError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.ServiceUnavailableError.super_"></a>[function <span class="apidocSignatureSpan">restify.ServiceUnavailableError.</span>super_ (options)](#apidoc.element.restify.ServiceUnavailableError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.StringClient"></a>[module restify.StringClient](#apidoc.module.restify.StringClient)

#### <a name="apidoc.element.restify.StringClient.StringClient"></a>[function <span class="apidocSignatureSpan">restify.</span>StringClient (options)](#apidoc.element.restify.StringClient.StringClient)
- description and source-code
```javascript
function StringClient(options) {
    assert.object(options, 'options');
    assert.optionalObject(options.gzip, 'options.gzip');

    options.accept = options.accept || 'text/plain';
    options.name = options.name || 'StringClient';
    options.contentType =
        options.contentType || 'application/x-www-form-urlencoded';

    HttpClient.call(this, options);
    this.gzip = options.gzip;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.StringClient.super_"></a>[function <span class="apidocSignatureSpan">restify.StringClient.</span>super_ (options)](#apidoc.element.restify.StringClient.super_)
- description and source-code
```javascript
function HttpClient(options) {
    assert.object(options, 'options');
    assert.optionalObject(options.headers, 'options.headers');
    assert.object(options.log, 'options.log');
    assert.optionalFunc(options.signRequest, 'options.signRequest');
    assert.optionalString(options.socketPath, 'options.socketPath');
    assert.optionalString(options.url, 'options.url');

    EventEmitter.call(this);

    var self = this;

    this.agent = options.agent;
    this.ca = options.ca;
    this.cert = options.cert;
    this.ciphers = options.ciphers;
    this.connectTimeout = options.connectTimeout || false;
    this.requestTimeout = options.requestTimeout || false;
    this.headers = options.headers || {};
    this.log = options.log;

    if (!this.log.serializers) {
        // Ensure logger has a reasonable serializer for 'client_res'
        // and 'client_req' logged in this module.
        this.log = this.log.child({serializers: bunyan.serializers});
    }
    this.key = options.key;
    this.name = options.name || 'HttpClient';
    this.passphrase = options.passphrase;
    this.pfx = options.pfx;

    if (options.rejectUnauthorized !== undefined) {
        this.rejectUnauthorized = options.rejectUnauthorized;
    } else {
        this.rejectUnauthorized = true;
    }

    this.retry = cloneRetryOptions(options.retry);
    this.signRequest = options.signRequest || false;
    this.socketPath = options.socketPath || false;
    this.url = options.url ? url.parse(options.url) : {};

    if (process.env.https_proxy) {
        this.proxy = url.parse(process.env.https_proxy);
    } else if (process.env.http_proxy) {
        this.proxy = url.parse(process.env.http_proxy);
    } else if (options.proxy) {
        this.proxy = options.proxy;
    } else {
        this.proxy = false;
    }

    if (this.proxy && !isProxyForURL(self.url)) {
        this.proxy = false;
    }

    if (options.accept) {
        if (options.accept.indexOf('/') === -1) {
            options.accept = mime.lookup(options.accept);
        }

        this.headers.accept = options.accept;
    }

    if (options.contentType) {
        if (options.contentType.indexOf('/') === -1) {
            options.type = mime.lookup(options.contentType);
        }

        this.headers['content-type'] = options.contentType;
    }

    if (options.userAgent !== false) {
        this.headers['user-agent'] = options.userAgent ||
            defaultUserAgent();
    }

    if (options.version) {
        this.headers['accept-version'] = options.version;
    }

    if (this.agent === undefined) {
        var Agent;
        var maxSockets;

        if (this.proxy) {
            if (this.url.protocol === 'https:') {
                if (this.proxy.protocol === 'https:') {
                    Agent = tunnelAgent.httpsOverHttps;
                } else {
                    Agent = tunnelAgent.httpsOverHttp;
                }
            } else {
                if (this.proxy.protocol === 'https:') {
                    Agent = tunnelAgent.httpOverHttps;
                } else {
                    Agent = tunnelAgent.httpOverHttp;
                }
            }
        } else if (this.url.protocol === 'https:') {
            Agent = KeepAliveAgentSecure;
            maxSockets = httpsMaxSockets;
        } else {
            Agent = KeepAliveAgent;
            maxSockets = httpMaxSockets;
        }

        if (this.proxy) {
            this.agent = new Agent({
                proxy: self.proxy,
                rejectUnauthorized: self.rejectUnauthorized,
                ca: self.ca
            });
        } else {
            this.agent = new Agent({
                cert: self.cert,
                ca: self.ca,
                ciphers: self.ciphers,
                key: self.key,
                maxSockets: maxSockets,

                // require('keep-alive-agent')
                maxKeepAliveRequests: 0,
                maxKeepAliveTime: 0,

                // native keepalive
                keepAliveMsecs: 1000,
                keepAlive: true,

                passphrase: self.passp ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.StringClient.prototype"></a>[module restify.StringClient.prototype](#apidoc.module.restify.StringClient.prototype)

#### <a name="apidoc.element.restify.StringClient.prototype.parse"></a>[function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>parse (req, callback)](#apidoc.element.restify.StringClient.prototype.parse)
- description and source-code
```javascript
function parse(req, callback) {
    function parseResponse(err, res) {
        var body = '';
        var gz;
        var hash;
        var md5;

        function done() {
            res.log.trace('body received:\n%s', body);
            res.body = body;

            if (hash && md5 !== hash.digest('base64')) {
                err = new Error('BadDigest');
                callback(err, req, res);
                return;
            }

            if (err) {
                err.body = body;
                err.message = body;
            }

            callback(err, req, res, body);
        }

        if (res) {
            md5 = res.headers['content-md5'];

            if (md5 && req.method !== 'HEAD' && res.statusCode !== 206) {
                hash = crypto.createHash('md5');
            }

            if (res.headers['content-encoding'] === 'gzip') {
                gz = zlib.createGunzip();
                gz.on('data', function (chunk) {
                    body += chunk.toString('utf8');
                });
                gz.once('end', done);
                res.once('end', gz.end.bind(gz));
            } else {
                res.setEncoding('utf8');
                res.once('end', done);
            }

            res.on('data', function onData(chunk) {
                if (hash) {
                    hash.update(chunk);
                }

                if (gz) {
                    gz.write(chunk);
                } else {
                    body += chunk;
                }
            });

        } else {
            callback(err, req, null, null);
        }
    }

    return (parseResponse);
}
```
- example usage
```shell
...
 * returns a parsed URL object.
 * @public
 * @function getUrl
 * @returns  {Object}
 */
Request.prototype.getUrl = function getUrl() {
    if (this._cacheURL !== this.url) {
        this._url = url.parse(this.url);
        this._cacheURL = this.url;
    }
    return (this._url);
};


/**
...
```

#### <a name="apidoc.element.restify.StringClient.prototype.patch"></a>[function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>patch (options, body, callback)](#apidoc.element.restify.StringClient.prototype.patch)
- description and source-code
```javascript
function patch(options, body, callback) {
    var opts = this._options('PATCH', options);

    if (typeof (body) === 'function') {
        callback = body;
        body = null;
    }

    return (this.write(opts, body, callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.StringClient.prototype.post"></a>[function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>post (options, body, callback)](#apidoc.element.restify.StringClient.prototype.post)
- description and source-code
```javascript
function post(options, body, callback) {
    var opts = this._options('POST', options);

    if (typeof (body) === 'function') {
        callback = body;
        body = null;
    }

    return (this.write(opts, body, callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.StringClient.prototype.put"></a>[function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>put (options, body, callback)](#apidoc.element.restify.StringClient.prototype.put)
- description and source-code
```javascript
function put(options, body, callback) {
    var opts = this._options('PUT', options);

    if (typeof (body) === 'function') {
        callback = body;
        body = null;
    }

    return (this.write(opts, body, callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.StringClient.prototype.read"></a>[function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>read (options, callback)](#apidoc.element.restify.StringClient.prototype.read)
- description and source-code
```javascript
function read(options, callback) {
    var self = this;
    this.request(options, function _parse(err, req) {
        if (err) {
            return (callback(err, req));
        }

        req.once('result', self.parse(req, callback));
        return (req.end());
    });
    return (this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.StringClient.prototype.write"></a>[function <span class="apidocSignatureSpan">restify.StringClient.prototype.</span>write (options, body, callback)](#apidoc.element.restify.StringClient.prototype.write)
- description and source-code
```javascript
function write(options, body, callback) {
    if (body !== null && typeof (body) !== 'string') {
        body = qs.stringify(body);
    }

    var self = this;

    function _write(data) {
        if (data) {
            var hash = crypto.createHash('md5');
            hash.update(data, 'utf8');
            options.headers['content-md5'] = hash.digest('base64');
        }

        self.request(options, function (err, req) {
            if (err) {
                callback(err, req);
                return;
            }

            req.once('result', self.parse(req, callback));
            req.end(data);
        });
    }

    options.headers = options.headers || {};

    if (this.gzip) {
        options.headers['accept-encoding'] = 'gzip';
    }

    if (body) {
        if (this.gzip) {
            options.headers['content-encoding'] = 'gzip';
            zlib.gzip(body, function (err, data) {
                if (err) {
                    callback(err, null);
                    return;
                }

                options.headers['content-length'] = data.length;
                _write(data);
            });
        } else {
            options.headers['content-length'] =
                Buffer.byteLength(body);
            _write(body);
        }
    } else {
        _write();
    }

    return (this);
}
```
- example usage
```shell
...
Object.keys(headers).forEach(function (k) {
    self.setHeader(k, headers[k]);
});

self.writeHead(self.statusCode);

if (self._data && !(isHead || code === 204 || code === 304)) {
    self.write(self._data);
}

self.end();

if (log.trace()) {
    log.trace({res: self}, 'response sent');
}
...
```



# <a name="apidoc.module.restify.TooManyRequestsError"></a>[module restify.TooManyRequestsError](#apidoc.module.restify.TooManyRequestsError)

#### <a name="apidoc.element.restify.TooManyRequestsError.TooManyRequestsError"></a>[function <span class="apidocSignatureSpan">restify.</span>TooManyRequestsError (cause, message)](#apidoc.element.restify.TooManyRequestsError.TooManyRequestsError)
- description and source-code
```javascript
TooManyRequestsError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.TooManyRequestsError.super_"></a>[function <span class="apidocSignatureSpan">restify.TooManyRequestsError.</span>super_ (options)](#apidoc.element.restify.TooManyRequestsError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.UnauthorizedError"></a>[module restify.UnauthorizedError](#apidoc.module.restify.UnauthorizedError)

#### <a name="apidoc.element.restify.UnauthorizedError.UnauthorizedError"></a>[function <span class="apidocSignatureSpan">restify.</span>UnauthorizedError (cause, message)](#apidoc.element.restify.UnauthorizedError.UnauthorizedError)
- description and source-code
```javascript
UnauthorizedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UnauthorizedError.super_"></a>[function <span class="apidocSignatureSpan">restify.UnauthorizedError.</span>super_ (options)](#apidoc.element.restify.UnauthorizedError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.UnavailableForLegalReasonsError"></a>[module restify.UnavailableForLegalReasonsError](#apidoc.module.restify.UnavailableForLegalReasonsError)

#### <a name="apidoc.element.restify.UnavailableForLegalReasonsError.UnavailableForLegalReasonsError"></a>[function <span class="apidocSignatureSpan">restify.</span>UnavailableForLegalReasonsError (cause, message)](#apidoc.element.restify.UnavailableForLegalReasonsError.UnavailableForLegalReasonsError)
- description and source-code
```javascript
UnavailableForLegalReasonsError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UnavailableForLegalReasonsError.super_"></a>[function <span class="apidocSignatureSpan">restify.UnavailableForLegalReasonsError.</span>super_ (options)](#apidoc.element.restify.UnavailableForLegalReasonsError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.UnorderedCollectionError"></a>[module restify.UnorderedCollectionError](#apidoc.module.restify.UnorderedCollectionError)

#### <a name="apidoc.element.restify.UnorderedCollectionError.UnorderedCollectionError"></a>[function <span class="apidocSignatureSpan">restify.</span>UnorderedCollectionError (cause, message)](#apidoc.element.restify.UnorderedCollectionError.UnorderedCollectionError)
- description and source-code
```javascript
UnorderedCollectionError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UnorderedCollectionError.super_"></a>[function <span class="apidocSignatureSpan">restify.UnorderedCollectionError.</span>super_ (options)](#apidoc.element.restify.UnorderedCollectionError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.UnprocessableEntityError"></a>[module restify.UnprocessableEntityError](#apidoc.module.restify.UnprocessableEntityError)

#### <a name="apidoc.element.restify.UnprocessableEntityError.UnprocessableEntityError"></a>[function <span class="apidocSignatureSpan">restify.</span>UnprocessableEntityError (cause, message)](#apidoc.element.restify.UnprocessableEntityError.UnprocessableEntityError)
- description and source-code
```javascript
UnprocessableEntityError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UnprocessableEntityError.super_"></a>[function <span class="apidocSignatureSpan">restify.UnprocessableEntityError.</span>super_ (options)](#apidoc.element.restify.UnprocessableEntityError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.UnsupportedMediaTypeError"></a>[module restify.UnsupportedMediaTypeError](#apidoc.module.restify.UnsupportedMediaTypeError)

#### <a name="apidoc.element.restify.UnsupportedMediaTypeError.UnsupportedMediaTypeError"></a>[function <span class="apidocSignatureSpan">restify.</span>UnsupportedMediaTypeError (cause, message)](#apidoc.element.restify.UnsupportedMediaTypeError.UnsupportedMediaTypeError)
- description and source-code
```javascript
UnsupportedMediaTypeError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UnsupportedMediaTypeError.super_"></a>[function <span class="apidocSignatureSpan">restify.UnsupportedMediaTypeError.</span>super_ (options)](#apidoc.element.restify.UnsupportedMediaTypeError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.UpgradeRequiredError"></a>[module restify.UpgradeRequiredError](#apidoc.module.restify.UpgradeRequiredError)

#### <a name="apidoc.element.restify.UpgradeRequiredError.UpgradeRequiredError"></a>[function <span class="apidocSignatureSpan">restify.</span>UpgradeRequiredError (cause, message)](#apidoc.element.restify.UpgradeRequiredError.UpgradeRequiredError)
- description and source-code
```javascript
UpgradeRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UpgradeRequiredError.super_"></a>[function <span class="apidocSignatureSpan">restify.UpgradeRequiredError.</span>super_ (options)](#apidoc.element.restify.UpgradeRequiredError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.UriTooLongError"></a>[module restify.UriTooLongError](#apidoc.module.restify.UriTooLongError)

#### <a name="apidoc.element.restify.UriTooLongError.UriTooLongError"></a>[function <span class="apidocSignatureSpan">restify.</span>UriTooLongError (cause, message)](#apidoc.element.restify.UriTooLongError.UriTooLongError)
- description and source-code
```javascript
UriTooLongError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.UriTooLongError.super_"></a>[function <span class="apidocSignatureSpan">restify.UriTooLongError.</span>super_ (options)](#apidoc.element.restify.UriTooLongError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.VariantAlsoNegotiatesError"></a>[module restify.VariantAlsoNegotiatesError](#apidoc.module.restify.VariantAlsoNegotiatesError)

#### <a name="apidoc.element.restify.VariantAlsoNegotiatesError.VariantAlsoNegotiatesError"></a>[function <span class="apidocSignatureSpan">restify.</span>VariantAlsoNegotiatesError (cause, message)](#apidoc.element.restify.VariantAlsoNegotiatesError.VariantAlsoNegotiatesError)
- description and source-code
```javascript
VariantAlsoNegotiatesError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.VariantAlsoNegotiatesError.super_"></a>[function <span class="apidocSignatureSpan">restify.VariantAlsoNegotiatesError.</span>super_ (options)](#apidoc.element.restify.VariantAlsoNegotiatesError.super_)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.WrongAcceptError"></a>[module restify.WrongAcceptError](#apidoc.module.restify.WrongAcceptError)

#### <a name="apidoc.element.restify.WrongAcceptError.WrongAcceptError"></a>[function <span class="apidocSignatureSpan">restify.</span>WrongAcceptError (cause, message)](#apidoc.element.restify.WrongAcceptError.WrongAcceptError)
- description and source-code
```javascript
WrongAcceptError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.WrongAcceptError.super_"></a>[function <span class="apidocSignatureSpan">restify.WrongAcceptError.</span>super_ (options)](#apidoc.element.restify.WrongAcceptError.super_)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.bunyan"></a>[module restify.bunyan](#apidoc.module.restify.bunyan)

#### <a name="apidoc.element.restify.bunyan.RequestCaptureStream"></a>[function <span class="apidocSignatureSpan">restify.bunyan.</span>RequestCaptureStream (opts)](#apidoc.element.restify.bunyan.RequestCaptureStream)
- description and source-code
```javascript
function RequestCaptureStream(opts) {
    assert.object(opts, 'options');
    assert.optionalObject(opts.stream, 'options.stream');
    assert.optionalArrayOfObject(opts.streams, 'options.streams');
    assert.optionalNumber(opts.level, 'options.level');
    assert.optionalNumber(opts.maxRecords, 'options.maxRecords');
    assert.optionalNumber(opts.maxRequestIds, 'options.maxRequestIds');
    assert.optionalBool(opts.dumpDefault, 'options.dumpDefault');

    var self = this;
    Stream.call(this);

    this.level = opts.level ? bunyan.resolveLevel(opts.level) : bunyan.WARN;
    this.limit = opts.maxRecords || 100;
    this.maxRequestIds = opts.maxRequestIds || 1000;
    this.requestMap = LRU({
        max: self.maxRequestIds
    });
    this.dumpDefault = opts.dumpDefault;

    this._offset = -1;
    this._rings = [];

    this.streams = [];

    if (opts.stream) {
        appendStream(this.streams, opts.stream);
    }

    if (opts.streams) {
        opts.streams.forEach(appendStream.bind(null, this.streams));
    }

    this.haveNonRawStreams = false;

    for (var i = 0; i < this.streams.length; i++) {
        if (!this.streams[i].raw) {
            this.haveNonRawStreams = true;
            break;
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.bunyan.createLogger"></a>[function <span class="apidocSignatureSpan">restify.bunyan.</span>createLogger (name)](#apidoc.element.restify.bunyan.createLogger)
- description and source-code
```javascript
function createLogger(name) {
    return (bunyan.createLogger({
        name: name,
        serializers: SERIALIZERS,
        streams: [
            {
                level: 'warn',
                stream: process.stderr
            },
            {
                level: 'debug',
                type: 'raw',
                stream: new RequestCaptureStream({
                    stream: process.stderr
                })
            }
        ]
    }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.bunyan.RequestCaptureStream"></a>[module restify.bunyan.RequestCaptureStream](#apidoc.module.restify.bunyan.RequestCaptureStream)

#### <a name="apidoc.element.restify.bunyan.RequestCaptureStream.RequestCaptureStream"></a>[function <span class="apidocSignatureSpan">restify.bunyan.</span>RequestCaptureStream (opts)](#apidoc.element.restify.bunyan.RequestCaptureStream.RequestCaptureStream)
- description and source-code
```javascript
function RequestCaptureStream(opts) {
    assert.object(opts, 'options');
    assert.optionalObject(opts.stream, 'options.stream');
    assert.optionalArrayOfObject(opts.streams, 'options.streams');
    assert.optionalNumber(opts.level, 'options.level');
    assert.optionalNumber(opts.maxRecords, 'options.maxRecords');
    assert.optionalNumber(opts.maxRequestIds, 'options.maxRequestIds');
    assert.optionalBool(opts.dumpDefault, 'options.dumpDefault');

    var self = this;
    Stream.call(this);

    this.level = opts.level ? bunyan.resolveLevel(opts.level) : bunyan.WARN;
    this.limit = opts.maxRecords || 100;
    this.maxRequestIds = opts.maxRequestIds || 1000;
    this.requestMap = LRU({
        max: self.maxRequestIds
    });
    this.dumpDefault = opts.dumpDefault;

    this._offset = -1;
    this._rings = [];

    this.streams = [];

    if (opts.stream) {
        appendStream(this.streams, opts.stream);
    }

    if (opts.streams) {
        opts.streams.forEach(appendStream.bind(null, this.streams));
    }

    this.haveNonRawStreams = false;

    for (var i = 0; i < this.streams.length; i++) {
        if (!this.streams[i].raw) {
            this.haveNonRawStreams = true;
            break;
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.bunyan.RequestCaptureStream.super_"></a>[function <span class="apidocSignatureSpan">restify.bunyan.RequestCaptureStream.</span>super_ ()](#apidoc.element.restify.bunyan.RequestCaptureStream.super_)
- description and source-code
```javascript
function Stream() {
  EE.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.bunyan.RequestCaptureStream.prototype"></a>[module restify.bunyan.RequestCaptureStream.prototype](#apidoc.module.restify.bunyan.RequestCaptureStream.prototype)

#### <a name="apidoc.element.restify.bunyan.RequestCaptureStream.prototype.toString"></a>[function <span class="apidocSignatureSpan">restify.bunyan.RequestCaptureStream.prototype.</span>toString ()](#apidoc.element.restify.bunyan.RequestCaptureStream.prototype.toString)
- description and source-code
```javascript
function toString() {
    return (sprintf(STR_FMT,
        this.constructor.name,
        this.level,
        this.limit,
        this.maxRequestIds));
}
```
- example usage
```shell
...
    // Client probes
    // method, url, headers, id
    'client-request': ['char *', 'char *', 'json', 'int'],

    // id, statusCode, headers
    'client-response': ['int', 'int', 'json'],

    // id, Error.toString()
    'client-error': ['id', 'char *']
};
var PROVIDER;


///--- API
...
```

#### <a name="apidoc.element.restify.bunyan.RequestCaptureStream.prototype.write"></a>[function <span class="apidocSignatureSpan">restify.bunyan.RequestCaptureStream.prototype.</span>write (record)](#apidoc.element.restify.bunyan.RequestCaptureStream.prototype.write)
- description and source-code
```javascript
function write(record) {
    var req_id = record.req_id || DEFAULT_REQ_ID;
    var ring;
    var self = this;

    if (!(ring = this.requestMap.get(req_id))) {
        if (++this._offset > this.maxRequestIds) {
            this._offset = 0;
        }

        if (this._rings.length <= this._offset) {
            this._rings.push(new bunyan.RingBuffer({
                limit: self.limit
            }));
        }

        ring = this._rings[this._offset];
        ring.records.length = 0;
        this.requestMap.set(req_id, ring);
    }

    assert.ok(ring, 'no ring found');

    if (record.level >= this.level) {
        var i, r, ser;

        for (i = 0; i < ring.records.length; i++) {
            r = ring.records[i];

            if (this.haveNonRawStreams) {
                ser = JSON.stringify(r,
                    bunyan.safeCycles()) + '\n';
            }
            self.streams.forEach(function (s) {
                s.stream.write(s.raw ? r : ser);
            });
        }
        ring.records.length = 0;

        if (this.dumpDefault) {
            var defaultRing = self.requestMap.get(DEFAULT_REQ_ID);

            for (i = 0; i < defaultRing.records.length; i++) {
                r = defaultRing.records[i];

                if (this.haveNonRawStreams) {
                    ser = JSON.stringify(r,
                        bunyan.safeCycles()) + '\n';
                }
                self.streams.forEach(function (s) {
                    s.stream.write(s.raw ? r : ser);
                });
            }
            defaultRing.records.length = 0;
        }
    } else {
        ring.write(record);
    }
}
```
- example usage
```shell
...
Object.keys(headers).forEach(function (k) {
    self.setHeader(k, headers[k]);
});

self.writeHead(self.statusCode);

if (self._data && !(isHead || code === 204 || code === 304)) {
    self.write(self._data);
}

self.end();

if (log.trace()) {
    log.trace({res: self}, 'response sent');
}
...
```



# <a name="apidoc.module.restify.bunyan.serializers"></a>[module restify.bunyan.serializers](#apidoc.module.restify.bunyan.serializers)

#### <a name="apidoc.element.restify.bunyan.serializers.client_req"></a>[function <span class="apidocSignatureSpan">restify.bunyan.serializers.</span>client_req (req)](#apidoc.element.restify.bunyan.serializers.client_req)
- description and source-code
```javascript
function clientReq(req) {
    if (!req) {
        return (req);
    }

    var host;

    try {
        host = req.host.split(':')[0];
    } catch (e) {
        host = false;
    }

    return ({
        method: req ? req.method : false,
        url: req ? req.path : false,
        address: host,
        port: req ? req.port : false,
        headers: req ? req.headers : false
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.bunyan.serializers.client_res"></a>[function <span class="apidocSignatureSpan">restify.bunyan.serializers.</span>client_res (res)](#apidoc.element.restify.bunyan.serializers.client_res)
- description and source-code
```javascript
function clientRes(res) {
    if (!res || !res.statusCode) {
        return (res);
    }

    return ({
        statusCode: res.statusCode,
        headers: res.headers
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.bunyan.serializers.err"></a>[function <span class="apidocSignatureSpan">restify.bunyan.serializers.</span>err (err)](#apidoc.element.restify.bunyan.serializers.err)
- description and source-code
```javascript
err = function (err) {
    if (!err || !err.stack)
        return err;
    var obj = {
        message: err.message,
        name: err.name,
        stack: getFullErrorStack(err),
        code: err.code,
        signal: err.signal
    }
    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.bunyan.serializers.req"></a>[function <span class="apidocSignatureSpan">restify.bunyan.serializers.</span>req (req)](#apidoc.element.restify.bunyan.serializers.req)
- description and source-code
```javascript
req = function (req) {
    if (!req || !req.connection)
        return req;
    return {
        method: req.method,
        url: req.url,
        headers: req.headers,
        remoteAddress: req.connection.remoteAddress,
        remotePort: req.connection.remotePort
    };
    // Trailers: Skipping for speed. If you need trailers in your app, then
    // make a custom serializer.
    //if (Object.keys(trailers).length > 0) {
    //  obj.trailers = req.trailers;
    //}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.bunyan.serializers.res"></a>[function <span class="apidocSignatureSpan">restify.bunyan.serializers.</span>res (res)](#apidoc.element.restify.bunyan.serializers.res)
- description and source-code
```javascript
res = function (res) {
    if (!res || !res.statusCode)
        return res;
    return {
        statusCode: res.statusCode,
        header: res._header
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.clients"></a>[module restify.clients](#apidoc.module.restify.clients)

#### <a name="apidoc.element.restify.clients.HttpClient"></a>[function <span class="apidocSignatureSpan">restify.clients.</span>HttpClient (options)](#apidoc.element.restify.clients.HttpClient)
- description and source-code
```javascript
function HttpClient(options) {
    assert.object(options, 'options');
    assert.optionalObject(options.headers, 'options.headers');
    assert.object(options.log, 'options.log');
    assert.optionalFunc(options.signRequest, 'options.signRequest');
    assert.optionalString(options.socketPath, 'options.socketPath');
    assert.optionalString(options.url, 'options.url');

    EventEmitter.call(this);

    var self = this;

    this.agent = options.agent;
    this.ca = options.ca;
    this.cert = options.cert;
    this.ciphers = options.ciphers;
    this.connectTimeout = options.connectTimeout || false;
    this.requestTimeout = options.requestTimeout || false;
    this.headers = options.headers || {};
    this.log = options.log;

    if (!this.log.serializers) {
        // Ensure logger has a reasonable serializer for 'client_res'
        // and 'client_req' logged in this module.
        this.log = this.log.child({serializers: bunyan.serializers});
    }
    this.key = options.key;
    this.name = options.name || 'HttpClient';
    this.passphrase = options.passphrase;
    this.pfx = options.pfx;

    if (options.rejectUnauthorized !== undefined) {
        this.rejectUnauthorized = options.rejectUnauthorized;
    } else {
        this.rejectUnauthorized = true;
    }

    this.retry = cloneRetryOptions(options.retry);
    this.signRequest = options.signRequest || false;
    this.socketPath = options.socketPath || false;
    this.url = options.url ? url.parse(options.url) : {};

    if (process.env.https_proxy) {
        this.proxy = url.parse(process.env.https_proxy);
    } else if (process.env.http_proxy) {
        this.proxy = url.parse(process.env.http_proxy);
    } else if (options.proxy) {
        this.proxy = options.proxy;
    } else {
        this.proxy = false;
    }

    if (this.proxy && !isProxyForURL(self.url)) {
        this.proxy = false;
    }

    if (options.accept) {
        if (options.accept.indexOf('/') === -1) {
            options.accept = mime.lookup(options.accept);
        }

        this.headers.accept = options.accept;
    }

    if (options.contentType) {
        if (options.contentType.indexOf('/') === -1) {
            options.type = mime.lookup(options.contentType);
        }

        this.headers['content-type'] = options.contentType;
    }

    if (options.userAgent !== false) {
        this.headers['user-agent'] = options.userAgent ||
            defaultUserAgent();
    }

    if (options.version) {
        this.headers['accept-version'] = options.version;
    }

    if (this.agent === undefined) {
        var Agent;
        var maxSockets;

        if (this.proxy) {
            if (this.url.protocol === 'https:') {
                if (this.proxy.protocol === 'https:') {
                    Agent = tunnelAgent.httpsOverHttps;
                } else {
                    Agent = tunnelAgent.httpsOverHttp;
                }
            } else {
                if (this.proxy.protocol === 'https:') {
                    Agent = tunnelAgent.httpOverHttps;
                } else {
                    Agent = tunnelAgent.httpOverHttp;
                }
            }
        } else if (this.url.protocol === 'https:') {
            Agent = KeepAliveAgentSecure;
            maxSockets = httpsMaxSockets;
        } else {
            Agent = KeepAliveAgent;
            maxSockets = httpMaxSockets;
        }

        if (this.proxy) {
            this.agent = new Agent({
                proxy: self.proxy,
                rejectUnauthorized: self.rejectUnauthorized,
                ca: self.ca
            });
        } else {
            this.agent = new Agent({
                cert: self.cert,
                ca: self.ca,
                ciphers: self.ciphers,
                key: self.key,
                maxSockets: maxSockets,

                // require('keep-alive-agent')
                maxKeepAliveRequests: 0,
                maxKeepAliveTime: 0,

                // native keepalive
                keepAliveMsecs: 1000,
                keepAlive: true,

                passphrase: self.passp ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.clients.JsonClient"></a>[function <span class="apidocSignatureSpan">restify.clients.</span>JsonClient (options)](#apidoc.element.restify.clients.JsonClient)
- description and source-code
```javascript
function JsonClient(options) {
    assert.object(options, 'options');

    options.accept = 'application/json';
    options.name = options.name || 'JsonClient';
    options.contentType = 'application/json';

    StringClient.call(this, options);

    this._super = StringClient.prototype;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.clients.StringClient"></a>[function <span class="apidocSignatureSpan">restify.clients.</span>StringClient (options)](#apidoc.element.restify.clients.StringClient)
- description and source-code
```javascript
function StringClient(options) {
    assert.object(options, 'options');
    assert.optionalObject(options.gzip, 'options.gzip');

    options.accept = options.accept || 'text/plain';
    options.name = options.name || 'StringClient';
    options.contentType =
        options.contentType || 'application/x-www-form-urlencoded';

    HttpClient.call(this, options);
    this.gzip = options.gzip;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.dtrace"></a>[module restify.dtrace](#apidoc.module.restify.dtrace)

#### <a name="apidoc.element.restify.dtrace.nextId"></a>[function <span class="apidocSignatureSpan">restify.dtrace.</span>nextId ()](#apidoc.element.restify.dtrace.nextId)
- description and source-code
```javascript
function nextId() {
    if (++ID >= MAX_INT) {
        ID = 1;
    }

    return (ID);
}
```
- example usage
```shell
...
 * @param    {Array}     chain array of handler functions
 * @param    {Function}  cb    callback function
 * @returns  {undefined}
 */
Server.prototype._run = function _run(req, res, route, chain, cb) {
var d;
var i = -1;
var id = dtrace.nextId();
req._dtraceId = id;

if (!req._anonFuncCount) {
    // Counter used to keep track of anonymous functions. Used when a
    // handler function is anonymous. This ensures we're using a
    // monotonically increasing int for anonymous handlers through out the
    // the lifetime of this request
...
```



# <a name="apidoc.module.restify.errors"></a>[module restify.errors](#apidoc.module.restify.errors)

#### <a name="apidoc.element.restify.errors.BadDigestError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>BadDigestError (cause, message)](#apidoc.element.restify.errors.BadDigestError)
- description and source-code
```javascript
BadDigestError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.BadGatewayError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>BadGatewayError (cause, message)](#apidoc.element.restify.errors.BadGatewayError)
- description and source-code
```javascript
BadGatewayError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.BadMethodError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>BadMethodError (cause, message)](#apidoc.element.restify.errors.BadMethodError)
- description and source-code
```javascript
BadMethodError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.BadRequestError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>BadRequestError (cause, message)](#apidoc.element.restify.errors.BadRequestError)
- description and source-code
```javascript
BadRequestError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.BandwidthLimitExceededError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>BandwidthLimitExceededError (cause, message)](#apidoc.element.restify.errors.BandwidthLimitExceededError)
- description and source-code
```javascript
BandwidthLimitExceededError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.ConflictError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>ConflictError (cause, message)](#apidoc.element.restify.errors.ConflictError)
- description and source-code
```javascript
ConflictError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.ExpectationFailedError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>ExpectationFailedError (cause, message)](#apidoc.element.restify.errors.ExpectationFailedError)
- description and source-code
```javascript
ExpectationFailedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.FailedDependencyError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>FailedDependencyError (cause, message)](#apidoc.element.restify.errors.FailedDependencyError)
- description and source-code
```javascript
FailedDependencyError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.ForbiddenError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>ForbiddenError (cause, message)](#apidoc.element.restify.errors.ForbiddenError)
- description and source-code
```javascript
ForbiddenError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.GatewayTimeoutError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>GatewayTimeoutError (cause, message)](#apidoc.element.restify.errors.GatewayTimeoutError)
- description and source-code
```javascript
GatewayTimeoutError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.GoneError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>GoneError (cause, message)](#apidoc.element.restify.errors.GoneError)
- description and source-code
```javascript
GoneError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.HttpError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>HttpError (options)](#apidoc.element.restify.errors.HttpError)
- description and source-code
```javascript
function HttpError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || HttpError;
    WError.apply(this, arguments);

    var self = this;
    var code = parseInt((options.statusCode || 500), 10);
    this.statusCode = code;
    this.body = options.body || {
        code: codeToErrorName(code),
        message: options.message || self.message
    };
    this.message = options.message || self.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.HttpVersionNotSupportedError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>HttpVersionNotSupportedError (cause, message)](#apidoc.element.restify.errors.HttpVersionNotSupportedError)
- description and source-code
```javascript
HttpVersionNotSupportedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.ImATeapotError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>ImATeapotError (cause, message)](#apidoc.element.restify.errors.ImATeapotError)
- description and source-code
```javascript
ImATeapotError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.InsufficientStorageError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>InsufficientStorageError (cause, message)](#apidoc.element.restify.errors.InsufficientStorageError)
- description and source-code
```javascript
InsufficientStorageError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.InternalError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>InternalError (cause, message)](#apidoc.element.restify.errors.InternalError)
- description and source-code
```javascript
InternalError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
...
        emittedError = true;
    } else {
        res.send(arg);
    }
    done = true;
} else if (typeof (arg) === 'string') { // GH-193, allow redirect
    if (req._rstfy_chained_route) {
        var _e = new errors.InternalError();
        log.error({
            err: _e
        }, 'Multiple next("chain") calls not ' +
            'supported');
        res.send(_e);
        return (false);
    }
...
```

#### <a name="apidoc.element.restify.errors.InternalServerError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>InternalServerError (cause, message)](#apidoc.element.restify.errors.InternalServerError)
- description and source-code
```javascript
InternalServerError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.InvalidArgumentError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>InvalidArgumentError (cause, message)](#apidoc.element.restify.errors.InvalidArgumentError)
- description and source-code
```javascript
InvalidArgumentError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.InvalidContentError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>InvalidContentError (cause, message)](#apidoc.element.restify.errors.InvalidContentError)
- description and source-code
```javascript
InvalidContentError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.InvalidCredentialsError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>InvalidCredentialsError (cause, message)](#apidoc.element.restify.errors.InvalidCredentialsError)
- description and source-code
```javascript
InvalidCredentialsError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.InvalidHeaderError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>InvalidHeaderError (cause, message)](#apidoc.element.restify.errors.InvalidHeaderError)
- description and source-code
```javascript
InvalidHeaderError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.InvalidVersionError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>InvalidVersionError (cause, message)](#apidoc.element.restify.errors.InvalidVersionError)
- description and source-code
```javascript
InvalidVersionError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.LengthRequiredError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>LengthRequiredError (cause, message)](#apidoc.element.restify.errors.LengthRequiredError)
- description and source-code
```javascript
LengthRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.LockedError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>LockedError (cause, message)](#apidoc.element.restify.errors.LockedError)
- description and source-code
```javascript
LockedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.LoopDetectedError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>LoopDetectedError (cause, message)](#apidoc.element.restify.errors.LoopDetectedError)
- description and source-code
```javascript
LoopDetectedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.MethodNotAllowedError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>MethodNotAllowedError (cause, message)](#apidoc.element.restify.errors.MethodNotAllowedError)
- description and source-code
```javascript
MethodNotAllowedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.MisdirectedRequestError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>MisdirectedRequestError (cause, message)](#apidoc.element.restify.errors.MisdirectedRequestError)
- description and source-code
```javascript
MisdirectedRequestError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.MissingParameterError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>MissingParameterError (cause, message)](#apidoc.element.restify.errors.MissingParameterError)
- description and source-code
```javascript
MissingParameterError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.NetworkAuthenticationRequiredError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>NetworkAuthenticationRequiredError (cause, message)](#apidoc.element.restify.errors.NetworkAuthenticationRequiredError)
- description and source-code
```javascript
NetworkAuthenticationRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.NotAcceptableError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>NotAcceptableError (cause, message)](#apidoc.element.restify.errors.NotAcceptableError)
- description and source-code
```javascript
NotAcceptableError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.NotAuthorizedError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>NotAuthorizedError (cause, message)](#apidoc.element.restify.errors.NotAuthorizedError)
- description and source-code
```javascript
NotAuthorizedError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.NotExtendedError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>NotExtendedError (cause, message)](#apidoc.element.restify.errors.NotExtendedError)
- description and source-code
```javascript
NotExtendedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.NotFoundError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>NotFoundError (cause, message)](#apidoc.element.restify.errors.NotFoundError)
- description and source-code
```javascript
NotFoundError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.NotImplementedError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>NotImplementedError (cause, message)](#apidoc.element.restify.errors.NotImplementedError)
- description and source-code
```javascript
NotImplementedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.PayloadTooLargeError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>PayloadTooLargeError (cause, message)](#apidoc.element.restify.errors.PayloadTooLargeError)
- description and source-code
```javascript
PayloadTooLargeError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.PaymentRequiredError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>PaymentRequiredError (cause, message)](#apidoc.element.restify.errors.PaymentRequiredError)
- description and source-code
```javascript
PaymentRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.PreconditionFailedError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>PreconditionFailedError (cause, message)](#apidoc.element.restify.errors.PreconditionFailedError)
- description and source-code
```javascript
PreconditionFailedError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.PreconditionRequiredError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>PreconditionRequiredError (cause, message)](#apidoc.element.restify.errors.PreconditionRequiredError)
- description and source-code
```javascript
PreconditionRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.ProxyAuthenticationRequiredError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>ProxyAuthenticationRequiredError (cause, message)](#apidoc.element.restify.errors.ProxyAuthenticationRequiredError)
- description and source-code
```javascript
ProxyAuthenticationRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.RangeNotSatisfiableError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>RangeNotSatisfiableError (cause, message)](#apidoc.element.restify.errors.RangeNotSatisfiableError)
- description and source-code
```javascript
RangeNotSatisfiableError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.RequestExpiredError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>RequestExpiredError (cause, message)](#apidoc.element.restify.errors.RequestExpiredError)
- description and source-code
```javascript
RequestExpiredError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.RequestHeaderFieldsTooLargeError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>RequestHeaderFieldsTooLargeError (cause, message)](#apidoc.element.restify.errors.RequestHeaderFieldsTooLargeError)
- description and source-code
```javascript
RequestHeaderFieldsTooLargeError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.RequestThrottledError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>RequestThrottledError (cause, message)](#apidoc.element.restify.errors.RequestThrottledError)
- description and source-code
```javascript
RequestThrottledError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.RequestTimeoutError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>RequestTimeoutError (cause, message)](#apidoc.element.restify.errors.RequestTimeoutError)
- description and source-code
```javascript
RequestTimeoutError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.ResourceNotFoundError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>ResourceNotFoundError (cause, message)](#apidoc.element.restify.errors.ResourceNotFoundError)
- description and source-code
```javascript
ResourceNotFoundError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.RestError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>RestError (options)](#apidoc.element.restify.errors.RestError)
- description and source-code
```javascript
function RestError(options) {
    assert.object(options, 'options');

    options.constructorOpt = options.constructorOpt || RestError;
    HttpError.apply(this, arguments);

    var self = this;
    this.restCode = options.restCode || 'Error';
    this.body = options.body || {
        code: self.restCode,
        message: options.message || self.message
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.ServiceUnavailableError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>ServiceUnavailableError (cause, message)](#apidoc.element.restify.errors.ServiceUnavailableError)
- description and source-code
```javascript
ServiceUnavailableError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.TooManyRequestsError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>TooManyRequestsError (cause, message)](#apidoc.element.restify.errors.TooManyRequestsError)
- description and source-code
```javascript
TooManyRequestsError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.UnauthorizedError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>UnauthorizedError (cause, message)](#apidoc.element.restify.errors.UnauthorizedError)
- description and source-code
```javascript
UnauthorizedError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.UnavailableForLegalReasonsError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>UnavailableForLegalReasonsError (cause, message)](#apidoc.element.restify.errors.UnavailableForLegalReasonsError)
- description and source-code
```javascript
UnavailableForLegalReasonsError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.UnorderedCollectionError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>UnorderedCollectionError (cause, message)](#apidoc.element.restify.errors.UnorderedCollectionError)
- description and source-code
```javascript
UnorderedCollectionError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.UnprocessableEntityError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>UnprocessableEntityError (cause, message)](#apidoc.element.restify.errors.UnprocessableEntityError)
- description and source-code
```javascript
UnprocessableEntityError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.UnsupportedMediaTypeError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>UnsupportedMediaTypeError (cause, message)](#apidoc.element.restify.errors.UnsupportedMediaTypeError)
- description and source-code
```javascript
UnsupportedMediaTypeError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.UpgradeRequiredError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>UpgradeRequiredError (cause, message)](#apidoc.element.restify.errors.UpgradeRequiredError)
- description and source-code
```javascript
UpgradeRequiredError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.UriTooLongError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>UriTooLongError (cause, message)](#apidoc.element.restify.errors.UriTooLongError)
- description and source-code
```javascript
UriTooLongError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.VariantAlsoNegotiatesError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>VariantAlsoNegotiatesError (cause, message)](#apidoc.element.restify.errors.VariantAlsoNegotiatesError)
- description and source-code
```javascript
VariantAlsoNegotiatesError = function (cause, message) {
    var index = 1;
    var opts = {
        statusCode: code
    };

    if (cause && cause instanceof Error) {
        opts.cause = cause;
        opts.constructorOpt = arguments.callee;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.constructorOpt = cause.constructorOpt;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || code;
    } else {
        opts.constructorOpt = arguments.callee;
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    HttpError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.WrongAcceptError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>WrongAcceptError (cause, message)](#apidoc.element.restify.errors.WrongAcceptError)
- description and source-code
```javascript
WrongAcceptError = function (cause, message) {
    var index = 1;
    var opts = {
        restCode: (k === 'Internal' ? 'InternalError' : k),
        statusCode: CODES[k]
    };

    opts.constructorOpt = arguments.callee;

    if (cause && cause instanceof Error) {
        opts.cause = cause;
    } else if (typeof (cause) === 'object') {
        opts.body = cause.body;
        opts.cause = cause.cause;
        opts.message = cause.message;
        opts.statusCode = cause.statusCode || CODES[k];
    } else {
        index = 0;
    }

    var args = slice(arguments, index);
    args.unshift(opts);
    RestError.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.errors.codeToHttpError"></a>[function <span class="apidocSignatureSpan">restify.errors.</span>codeToHttpError (code, message, body)](#apidoc.element.restify.errors.codeToHttpError)
- description and source-code
```javascript
function codeToHttpError(code, message, body) {
    var err;
    var name = codeToErrorName(code);

    if (!name) {
        err = new HttpError({
            statusCode: code,
            message: message,
            body: body
        });
        err.name = 'Http' + code + 'Error';
    } else {
        err = new module.exports[name]({
            body: body,
            message: message,
            constructorOpt: codeToHttpError,
            statusCode: code
        });
    }

    return (err);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.formatters"></a>[module restify.formatters](#apidoc.module.restify.formatters)



# <a name="apidoc.module.restify.plugins"></a>[module restify.plugins](#apidoc.module.restify.plugins)

#### <a name="apidoc.element.restify.plugins.CORS"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>CORS (opts)](#apidoc.element.restify.plugins.CORS)
- description and source-code
```javascript
function cors(opts) {
    assert.optionalObject(opts, 'options');
    opts = opts || {};
    assert.optionalArrayOfString(opts.origins, 'options.origins');
    assert.optionalBool(opts.credentials, 'options.credentials');
    assert.optionalArrayOfString(opts.headers, 'options.headers');

    cors.credentials = opts.credentials;
    cors.origins = opts.origins || ['*'];

    var headers = (opts.headers || []).slice(0);
    var origins = opts.origins || ['*'];

    EXPOSE_HEADERS.forEach(function (h) {
        if (headers.indexOf(h) === -1) {
            headers.push(h);
        }
    });

    // Handler for simple requests
    function restifyCORSSimple(req, res, next) {
        var origin;

        if (!(origin = matchOrigin(req, origins))) {
            next();
            return;
        }

        function corsOnHeader() {
            origin = req.headers.origin;

            if (opts.credentials) {
                res.setHeader(AC_ALLOW_ORIGIN, origin);
                res.setHeader(AC_ALLOW_CREDS, 'true');
            } else {
                res.setHeader(AC_ALLOW_ORIGIN, origin);
            }

            res.setHeader(AC_EXPOSE_HEADERS, headers.join(', '));
        }

        res.once('header', corsOnHeader);
        next();
    }

    return (restifyCORSSimple);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.acceptParser"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>acceptParser (acceptable)](#apidoc.element.restify.plugins.acceptParser)
- description and source-code
```javascript
function acceptParser(acceptable) {
    if (!Array.isArray(acceptable)) {
        acceptable = [acceptable];
    }
    assert.arrayOfString(acceptable, 'acceptable');

    acceptable = acceptable.filter(function (a) {
        return (a);
    }).map(function (a) {
            return ((a.indexOf('/') === -1) ? mime.lookup(a) : a);
        }).filter(function (a) {
            return (a);
        });

    var e = new NotAcceptableError('Server accepts: ' + acceptable.join());

    function parseAccept(req, res, next) {
        if (req.accepts(acceptable)) {
            next();
            return;
        }

        res.json(e);
        next(false);
    }

    return (parseAccept);
}
```
- example usage
```shell
...
'''javascript
var restify = require('restify');

var server = restify.createServer({
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});
...
```

#### <a name="apidoc.element.restify.plugins.auditLogger"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>auditLogger (options)](#apidoc.element.restify.plugins.auditLogger)
- description and source-code
```javascript
function auditLogger(options) {
    assert.object(options, 'options');
    assert.object(options.log, 'options.log');
    var errSerializer = bunyan.stdSerializers.err;

    if (options.log.serializers && options.log.serializers.err) {
        errSerializer = options.log.serializers.err;
    }

    var log = options.log.child({
        audit: true,
        serializers: {
            err: errSerializer,
            req: function auditRequestSerializer(req) {
                if (!req) {
                    return (false);
                }

                var timers = {};
                (req.timers || []).forEach(function (time) {
                    var t = time.time;
                    var _t = Math.floor((1000000 * t[0]) +
                        (t[1] / 1000));
                    timers[time.name] = _t;
                });
                return ({
                    // account for native and queryParser plugin usage
                    query: (typeof req.query === 'function') ?
                            req.query() : req.query,
                    method: req.method,
                    url: req.url,
                    headers: req.headers,
                    httpVersion: req.httpVersion,
                    trailers: req.trailers,
                    version: req.version(),
                    body: options.body === true ?
                        req.body : undefined,
                    timers: timers
                });
            },
            res: function auditResponseSerializer(res) {
                if (!res) {
                    return (false);
                }


                var body;

                if (options.body === true) {
                    if (res._body instanceof HttpError) {
                        body = res._body.body;
                    } else {
                        body = res._body;
                    }
                }

                return ({
                    statusCode: res.statusCode,
                    headers: res._headers,
                    trailer: res._trailer || false,
                    body: body
                });
            }
        }
    });

    function audit(req, res, route, err) {
        var latency = res.get('Response-Time');

        if (typeof (latency) !== 'number') {
            latency = Date.now() - req._time;
        }

        var obj = {
            remoteAddress: req.connection.remoteAddress,
            remotePort: req.connection.remotePort,
            req_id: req.getId(),
            req: req,
            res: res,
            err: err,
            latency: latency,
            secure: req.secure,
            _audit: true
        };

        log.info(obj, 'handled: %d', res.statusCode);

        return (true);
    }

    return (audit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.authorizationParser"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>authorizationParser (options)](#apidoc.element.restify.plugins.authorizationParser)
- description and source-code
```javascript
function authorizationParser(options) {

    function parseAuthorization(req, res, next) {
        req.authorization = {};
        req.username = 'anonymous';

        if (!req.headers.authorization) {
            return (next());
        }

        var pieces = req.headers.authorization.split(' ', 2);

        if (!pieces || pieces.length !== 2) {
            var e = new InvalidHeaderError('BasicAuth content ' +
                'is invalid.');
            return (next(e));
        }

        req.authorization.scheme = pieces[0];
        req.authorization.credentials = pieces[1];

        try {
            switch (pieces[0].toLowerCase()) {
                case 'basic':
                    req.authorization.basic = parseBasic(pieces[1]);
                    req.username = req.authorization.basic.username;
                    break;

                case 'signature':
                    req.authorization.signature =
                        parseSignature(req, options);
                    req.username =
                        req.authorization.signature.keyId;
                    break;

                default:
                    break;
            }
        } catch (e2) {
            return (next(e2));
        }

        return (next());
    }

    return (parseAuthorization);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.bodyParser"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>bodyParser (options)](#apidoc.element.restify.plugins.bodyParser)
- description and source-code
```javascript
function bodyParser(options) {
    assert.optionalObject(options, 'options');
    options = options || {};
    options.bodyReader = true;

    var read = bodyReader(options);
    var parseForm = formParser(options);
    var parseJson = jsonParser(options);
    var parseMultipart = multipartParser(options);
    var parseFieldedText = fieldedTextParser(options);

    function parseBody(req, res, next) {
        // Allow use of 'requestBodyOnGet' flag to allow for merging of
        // the request body of a GET request into req.params
        if (req.method === 'HEAD') {
            next();
            return;
        }

        if (req.method === 'GET') {
            if (!options.requestBodyOnGet) {
                next();
                return;
            }
        }

        if (req.contentLength() === 0 && !req.isChunked()) {
            next();
            return;
        }

        var parser;
        var type = req.contentType().toLowerCase();

        switch (type) {
            case 'application/json':
                parser = parseJson[0];
                break;
            case 'application/x-www-form-urlencoded':
                parser = parseForm[0];
                break;
            case 'multipart/form-data':
                parser = parseMultipart;
                break;
            case 'text/tsv':
                parser = parseFieldedText;
                break;
            case 'text/tab-separated-values':
                parser = parseFieldedText;
                break;
            case 'text/csv':
                parser = parseFieldedText;
                break;

            default:
                break;
        }

        if (parser) {
            parser(req, res, next);
        } else if (options && options.rejectUnknown) {
            next(new UnsupportedMediaTypeError(type));
        } else {
            next();
        }
    }

    return ([read, parseBody]);
}
```
- example usage
```shell
...

var server = restify.createServer({
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});

server.listen(8080, function () {
...
```

#### <a name="apidoc.element.restify.plugins.conditionalRequest"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>conditionalRequest ()](#apidoc.element.restify.plugins.conditionalRequest)
- description and source-code
```javascript
function conditionalRequest() {
    var chain = [
        checkIfMatch,
        checkIfNoneMatch,
        checkIfModified,
        checkIfUnmodified
    ];
    return (chain);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.dateParser"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>dateParser (clockSkew)](#apidoc.element.restify.plugins.dateParser)
- description and source-code
```javascript
function dateParser(clockSkew) {
    if (!clockSkew) {
        clockSkew = 300;
    }
    assert.number(clockSkew, 'clockSkew');

    clockSkew = clockSkew * 1000;

    function parseDate(req, res, next) {
        if (!req.headers.date) {
            return (next());
        }

        var e;
        var date = req.headers.date;
        var log = req.log;

        try {
            var now = Date.now();
            var sent = new Date(date).getTime();

            if (log.trace()) {
                log.trace({
                    allowedSkew: clockSkew,
                    now: now,
                    sent: sent
                }, 'Checking clock skew');
            }

            if ((now - sent) > clockSkew) {
                e = new RequestExpiredError(OLD_MSG, date);
                return (next(e));
            }


        } catch (err) {
            log.trace({
                err: err
            }, 'Bad Date header: %s', date);

            e = new InvalidHeaderError(BAD_MSG, date);
            return (next(e));
        }

        return (next());
    }

    return (parseDate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.fullResponse"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>fullResponse ()](#apidoc.element.restify.plugins.fullResponse)
- description and source-code
```javascript
function fullResponse() {
    function restifyResponseHeaders(req, res, next) {
        res.once('header', function () {

            // Restify 1.0 compatibility
            if (res.defaultResponseFormatters) {
                res.defaultResponseFormatters(res._data);
            }

            res.emit('beforeSend', res._data, res._body);

            // end backwards-compatibility
            return (setHeaders(req, res));
        });

        return (next());
    }

    return (restifyResponseHeaders);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.gzipResponse"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>gzipResponse (opts)](#apidoc.element.restify.plugins.gzipResponse)
- description and source-code
```javascript
function gzipResponse(opts) {
    assert.optionalObject(opts, 'options');

    function gzip(req, res, next) {
        if (!req.acceptsEncoding('gzip')) {
            next();
            return;
        }

        var gz = zlib.createGzip(opts);

        gz.on('data', res.write.bind(res));
        gz.once('end', res.end.bind(res));
        gz.on('drain', res.emit.bind(res, 'drain'));

        var origWrite = res.write;
        var origEnd = res.end;
        var origWriteHead = res.writeHead;
        res.handledGzip = function _handledGzip() {
            res.write = origWrite;
            res.end = origEnd;
            res.writeHead = origWriteHead;
        };

        res.write = gz.write.bind(gz);
        res.end = gz.end.bind(gz);

        res.writeHead = _writeHead.bind(res, res.writeHead);
        res.setHeader('Content-Encoding', 'gzip');
        next();
    }

    return (gzip);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.jsonBodyParser"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>jsonBodyParser (options)](#apidoc.element.restify.plugins.jsonBodyParser)
- description and source-code
```javascript
function jsonBodyParser(options) {
    assert.optionalObject(options, 'options');
    options = options || {};

    var override = options.overrideParams;

    function parseJson(req, res, next) {
        if (req.getContentType() !== 'application/json' || !req.body) {
            next();
            return;
        }

        var params;

        try {
            params = JSON.parse(req.body, options.reviver);
        } catch (e) {
            next(new errors.InvalidContentError('Invalid JSON: ' +
                e.message));
            return;
        }

        if (options.mapParams !== false) {
            if (Array.isArray(params)) {
                req.params = params;
            } else if (typeof (params) === 'object' && params !== null) {
                Object.keys(params).forEach(function (k) {
                    var p = req.params[k];

                    if (p && !override) {
                        return (false);
                    }
                    req.params[k] = params[k];
                    return (true);
                });
            } else {
                req.params = params || req.params;
            }
        } else {
            req._body = req.body;
        }

        req.body = params;

        next();
    }

    var chain = [];

    if (!options.bodyReader) {
        chain.push(bodyReader(options));
    }
    chain.push(parseJson);
    return (chain);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.jsonp"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>jsonp ()](#apidoc.element.restify.plugins.jsonp)
- description and source-code
```javascript
function jsonp() {
    function _jsonp(req, res, next) {
        var q = req.getQuery();

        // If the query plugin wasn't used, we need to hack it in now
        if (typeof (q) === 'string') {
            req.query = qs.parse(q);
        }

        if (req.query.callback || req.query.jsonp) {
            res.setHeader('Content-Type', 'application/javascript');
        }

        next();
    }

    return (_jsonp);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.multipartBodyParser"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>multipartBodyParser (options)](#apidoc.element.restify.plugins.multipartBodyParser)
- description and source-code
```javascript
function multipartBodyParser(options) {
    if (!options) {
        options = {};
    }
    assert.object(options, 'options');
    assert.optionalBool(options.overrideParams, 'options.overrideParams');
    assert.optionalBool(options.multiples, 'options.multiples');
    assert.optionalBool(options.keepExtensions, 'options.keepExtensions');
    assert.optionalString(options.uploadDir, 'options.uploadDir');
    assert.optionalNumber(options.maxFieldsSize, 'options.maxFieldsSize');
    assert.optionalString(options.hash, 'options.hash');
    assert.optionalFunc(options.multipartFileHandler,
                        'options.multipartFileHandler');
    assert.optionalFunc(options.multipartHandler, 'options.multipartHandler');
    assert.optionalBool(options.mapParams, 'options.mapParams');
    assert.optionalBool(options.mapFiles, 'options.mapFiles');

    var override = options.overrideParams;

    function parseMultipartBody(req, res, next) {
        next = once(next);

        if (req.getContentType() !== 'multipart/form-data' ||
            (req.getContentLength() === 0 && !req.isChunked())) {
            return (next());
        }

        var form = new formidable.IncomingForm();

        // enable multiple files on a single upload field
        // (html5 multiple attribute)
        form.multiples = options.multiples || false;
        form.keepExtensions = options.keepExtensions ? true : false;

        if (options.uploadDir) {
            form.uploadDir = options.uploadDir;
        }

        if (options.maxFieldsSize) {
            form.maxFieldsSize = options.maxFieldsSize;
        }

        if (options.hash) {
            form.hash = options.hash;
        }

        form.onPart = function onPart(part) {
            if (part.filename && options.multipartFileHandler) {
                options.multipartFileHandler(part, req);
            } else if (!part.filename && options.multipartHandler) {
                options.multipartHandler(part, req);
            } else {
                form.handlePart(part);
            }
        };

        form.parse(req, function (err, fields, files) {
            if (err) {
                return (next(new errors.BadRequestError(err.message)));
            }

            req.body = fields;
            req.files = files;

            if (options.mapParams !== false) {
                Object.keys(fields).forEach(function (k) {
                    if (req.params[k] && !override) {
                        return;
                    }

                    req.params[k] = fields[k];
                });

                if (options.mapFiles) {
                    var barrier = vasync.barrier();
                    barrier.on('drain', function () {
                        return next();
                    });

                    barrier.start('fs');
                    Object.keys(files).forEach(function (f) {
                        if (req.params[f] && !override) {
                            return;
                        }
                        barrier.start('fs' + f);
                        fs.readFile(files[f].path, function (ex, data) {
                            barrier.done('fs' + f);
<span class="apidocCodeCommentSpan">                            /*
                             * We want to stop the request here, if there's an
                             * error trying to read the file from disk.
                             * Ideally we'd like to stop the other oustanding
                             * file reads too, but there's no way to cancel in
                             * flight fs reads.  So we just return an error, and
                             * be grudgingly let the other file reads finish.
                             */
</span>                            if (ex) {
                                return next(new errors.InternalError(ex,
                                         'unable to read file' + f));
                            }
                            req.params[f] = data;
                            return (true);
                        });
                    });
                    ba ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.queryParser"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>queryParser (options)](#apidoc.element.restify.plugins.queryParser)
- description and source-code
```javascript
function queryParser(options) {
    if (!options) {
        options = {};
    }
    assert.object(options, 'options');

<span class="apidocCodeCommentSpan">    /*
     * Releases of restify 4.x up to 4.1.1 used qs@3 which effectively defaulted
     * to 'plainObjects=true' and 'allowDots=true'. To maintain backward
     * compatibility for the restify 4.x stream while using the latest qs
     * version, we need to maintain those defaults. Note that restify-plugins
     * changes back to the pre-restify-4.x behaviour. See test/query.test.js
     * for more details.
     */
</span>    var qsOptions = {
        plainObjects: true,
        allowDots: true
    };
    Object.keys(EXPOSED_QS_OPTIONS).forEach(function (k) {
        EXPOSED_QS_OPTIONS[k](options[k], k); // assert type of this option

        if (options.hasOwnProperty(k)) {
            qsOptions[k] = options[k];
        }
    });

    function parseQueryString(req, res, next) {
        if (!req.getQuery()) {
            req.query = {};
            return (next());
        }

        req.query = qs.parse(req.getQuery(), qsOptions);

        if (options.mapParams !== false) {
            Object.keys(req.query).forEach(function (k) {
                if (req.params[k] && !options.overrideParams) {
                    return (false);
                }

                req.params[k] = req.query[k];
                return (true);
            });
        }

        return (next());
    }

    return (parseQueryString);
}
```
- example usage
```shell
...
var restify = require('restify');

var server = restify.createServer({
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});
...
```

#### <a name="apidoc.element.restify.plugins.requestExpiry"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>requestExpiry (options)](#apidoc.element.restify.plugins.requestExpiry)
- description and source-code
```javascript
function requestExpiry(options) {
    assert.object(options, 'options');
    assert.string(options.header, 'options.header');
    var headerKey = options.header;

    return function (req, res, next) {
        var expiry = req.headers[headerKey];

        if (expiry) {
            var expiryTime = Number(expiry);

            // The request has expired
            if (Date.now() > expiryTime) {
                return next(new GatewayTimeoutError('Request has expired'));
            }
        }

        // Happy case
        return next();
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.requestLogger"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>requestLogger (options)](#apidoc.element.restify.plugins.requestLogger)
- description and source-code
```javascript
function requestLogger(options) {
    assert.optionalObject(options);
    options = options || {};

    var props;

    if (options.properties) {
        props = shallowCopy(options.properties);
    } else {
        props = {};
    }

    if (options.serializers) {
        props.serializers = options.serializers;
    }

    var headersToCopy = options.headers || [];

    return function bunyan(req, res, next) {
        if (!req.log && !options.log) {
            next();
            return;
        }

        var log = req.log || options.log;

        props.req_id = req.getId();
        headersToCopy.forEach(function (k) {

            if (req.headers[k]) {
                props[k] = req.headers[k];
            }
        });
        req.log = log.child(props, props.serializers ? false : true);

        if (props.req_id) {
            delete props.req_id;
        }

        next();
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.sanitizePath"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>sanitizePath (options)](#apidoc.element.restify.plugins.sanitizePath)
- description and source-code
```javascript
function sanitizePath(options) {
    options = options || {};

    function _sanitizePath(req, res, next) {
        req.url = strip(req.url);
        next();
    }

    return (_sanitizePath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.serveStatic"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>serveStatic (opts)](#apidoc.element.restify.plugins.serveStatic)
- description and source-code
```javascript
function serveStatic(opts) {
    opts = opts || {};
    assert.object(opts, 'options');
    assert.string(opts.directory, 'options.directory');
    assert.optionalNumber(opts.maxAge, 'options.maxAge');
    assert.optionalObject(opts.match, 'options.match');
    assert.optionalString(opts.charSet, 'options.charSet');
    assert.optionalString(opts.file, 'options.file');

    var p = path.normalize(opts.directory).replace(/\\/g, '/');
    var re = new RegExp('^' + escapeRE(p) + '/?.*');

    function serveFileFromStats(file, err, stats, isGzip, req, res, next) {
        if (err) {
            next(new ResourceNotFoundError(err,
                req.path()));
            return;
        } else if (!stats.isFile()) {
            next(new ResourceNotFoundError('%s does not exist', req.path()));
            return;
        }

        if (res.handledGzip && isGzip) {
            res.handledGzip();
        }

        var fstream = fs.createReadStream(file + (isGzip ? '.gz' : ''));
        var maxAge = opts.maxAge === undefined ? 3600 : opts.maxAge;
        fstream.once('open', function (fd) {
            res.cache({maxAge: maxAge});
            res.set('Content-Length', stats.size);
            res.set('Content-Type', mime.lookup(file));
            res.set('Last-Modified', stats.mtime);

            if (opts.charSet) {
                var type = res.getHeader('Content-Type') +
                    '; charset=' + opts.charSet;
                res.setHeader('Content-Type', type);
            }

            if (opts.etag) {
                res.set('ETag', opts.etag(stats, opts));
            }
            res.writeHead(200);
            fstream.pipe(res);
            fstream.once('end', function () {
                next(false);
            });
        });
    }

    function serveNormal(file, req, res, next) {
        fs.stat(file, function (err, stats) {
            if (!err && stats.isDirectory() && opts.default) {
                // Serve an index.html page or similar
                file = path.join(file, opts.default);
                fs.stat(file, function (dirErr, dirStats) {
                    serveFileFromStats(file,
                        dirErr,
                        dirStats,
                        false,
                        req,
                        res,
                        next);
                });
            } else {
                serveFileFromStats(file,
                    err,
                    stats,
                    false,
                    req,
                    res,
                    next);
            }
        });
    }

    function serve(req, res, next) {
        var file;

        if (opts.file) {
            //serves a direct file
            file = path.join(opts.directory,
                decodeURIComponent(opts.file));
        } else {
            file = path.join(opts.directory,
                decodeURIComponent(req.path()));
        }

        if (req.method !== 'GET' && req.method !== 'HEAD') {
            next(new MethodNotAllowedError(req.method));
            return;
        }

        if (!re.test(file.replace(/\\/g, '/'))) {
            next(new NotAuthorizedError(req.path()));
            return;
        }

        if (opts.match && !opts.match.test(file)) {
            next(new NotAuthorizedError(req.path()));
            return;
        }

        if (opts.gzip && req.acceptsEncoding('gzip')) {
            fs.stat(file + '.gz', function (err, stats) {
                if (!err) {
                    res.setHeader('Content-Encoding', 'gzip');
                    serveFileFromStats(file,
                        err,
                        stats,
                        true,
                        req,
                        res,
                        next);
                } else {
                    serveNormal(file, req, res, next);
                }
            });
        } else {
            serveNormal(file, req, res, next);
        }

    }

    return (serve);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.throttle"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>throttle (options)](#apidoc.element.restify.plugins.throttle)
- description and source-code
```javascript
function throttle(options) {
    assert.object(options, 'options');
    assert.number(options.burst, 'options.burst');
    assert.number(options.rate, 'options.rate');

    if (!xor(options.ip, options.xff, options.username)) {
        throw new Error('(ip ^ username ^ xff)');
    }

    var table = options.tokensTable ||
        new TokenTable({size: options.maxKeys});

    function rateLimit(req, res, next) {
        var attr;
        var burst = options.burst;
        var rate = options.rate;

        if (options.ip) {
            attr = req.connection.remoteAddress;
        } else if (options.xff) {
            attr = req.headers['x-forwarded-for'];
        } else if (options.username) {
            attr = req.username;
        } else {
            req.log.warn({config: options},
                'Invalid throttle configuration');
            return (next());
        }

        // Before bothering with overrides, see if this request
        // even matches
        if (!attr) {
            return (next());
        }

        // Check the overrides
        if (options.overrides &&
            options.overrides[attr] &&
            options.overrides[attr].burst !== undefined &&
            options.overrides[attr].rate !== undefined) {

            burst = options.overrides[attr].burst;
            rate = options.overrides[attr].rate;
        }

        if (!rate || !burst) {
            return (next());
        }

        var bucket = table.get(attr);

        if (!bucket) {
            bucket = new TokenBucket({
                capacity: burst,
                fillRate: rate
            });
            table.put(attr, bucket);
        }

        req.log.trace('Throttle(%s): num_tokens= %d',
            attr, bucket.tokens);

        if (!bucket.consume(1)) {
            req.log.info({
                address: req.connection.remoteAddress || '?',
                method: req.method,
                url: req.url,
                user: req.username || '?'
            }, 'Throttling');

            var msg = sprintf(MESSAGE, rate);
            return (next(new TooManyRequestsError(msg)));
        }

        return (next());
    }

    return (rateLimit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.plugins.urlEncodedBodyParser"></a>[function <span class="apidocSignatureSpan">restify.plugins.</span>urlEncodedBodyParser (options)](#apidoc.element.restify.plugins.urlEncodedBodyParser)
- description and source-code
```javascript
function urlEncodedBodyParser(options) {
    options = options || {};
    assert.object(options, 'options');

    var override = options.overrideParams;

    function parseUrlEncodedBody(req, res, next) {
        if (req.getContentType() !== MIME_TYPE || !req.body) {
            next();
            return;
        }

        try {
            var params = querystring.parse(req.body);

            if (options.mapParams !== false) {
                var keys = Object.keys(params);
                keys.forEach(function (k) {
                    var p = req.params[k];

                    if (p && !override) {
                        return (false);
                    }

                    req.params[k] = params[k];
                    return (true);
                });
            } else {
                req._body = req.body;
                req.body = params;
            }
        } catch (e) {
            next(new errors.InvalidContentError(e.message));
            return;
        }

        req.log.trace('req.params now: %j', req.params);
        next();
    }

    var chain = [];

    if (!options.bodyReader) {
        chain.push(bodyReader(options));
    }
    chain.push(parseUrlEncodedBody);
    return (chain);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.pre"></a>[module restify.pre](#apidoc.module.restify.pre)

#### <a name="apidoc.element.restify.pre.pause"></a>[function <span class="apidocSignatureSpan">restify.pre.</span>pause ()](#apidoc.element.restify.pre.pause)
- description and source-code
```javascript
function pause() {

    function prePause(req, res, next) {
        pauseStream(req);
        next();
    }

    return (prePause);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.pre.sanitizePath"></a>[function <span class="apidocSignatureSpan">restify.pre.</span>sanitizePath (options)](#apidoc.element.restify.pre.sanitizePath)
- description and source-code
```javascript
function sanitizePath(options) {
    options = options || {};

    function _sanitizePath(req, res, next) {
        req.url = strip(req.url);
        next();
    }

    return (_sanitizePath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.pre.userAgentConnection"></a>[function <span class="apidocSignatureSpan">restify.pre.</span>userAgentConnection (opts)](#apidoc.element.restify.pre.userAgentConnection)
- description and source-code
```javascript
function userAgentConnection(opts) {
    assert.optionalObject(opts, 'options');
    opts = opts || {};
    assert.optionalObject(opts.userAgentRegExp, 'options.userAgentRegExp');

    var re = opts.userAgentRegExp;

    if (!re) {
        re = /^curl.+/;
    }

    function handleUserAgent(req, res, next) {
        var ua = req.headers['user-agent'];

        if (ua && re.test(ua)) {
            res.setHeader('Connection', 'close');
        }

        if (req.method === 'HEAD') {
            res.once('header',
                res.removeHeader.bind(res, 'content-length'));
        }

        next();
    }

    return (handleUserAgent);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.router"></a>[module restify.router](#apidoc.module.restify.router)

#### <a name="apidoc.element.restify.router.router"></a>[function <span class="apidocSignatureSpan">restify.</span>router (options)](#apidoc.element.restify.router.router)
- description and source-code
```javascript
function Router(options) {
    assert.object(options, 'options');
    assert.object(options.log, 'options.log');

    EventEmitter.call(this);

    this.cache = LRU({max: 100});
    this.contentType = options.contentType || [];

    if (!Array.isArray(this.contentType)) {
        this.contentType = [this.contentType];
    }
    assert.arrayOfString(this.contentType, 'options.contentType');

    this.log = options.log;
    this.mounts = {};
    this.name = 'RestifyRouter';

    // A list of methods to routes
    this.routes = {
        DELETE: [],
        GET: [],
        HEAD: [],
        OPTIONS: [],
        PATCH: [],
        POST: [],
        PUT: []
    };

    // So we can retrun 405 vs 404, we maintain a reverse mapping of URLs
    // to method
    this.reverse = {};

    this.versions = options.versions || options.version || [];

    if (!Array.isArray(this.versions)) {
        this.versions = [this.versions];
    }
    assert.arrayOfString(this.versions, 'options.versions');

    this.versions.forEach(function (v) {
        if (semver.valid(v)) {
            return (true);
        }

        throw new InvalidArgumentError('%s is not a valid semver', v);
    });
    this.versions.sort();

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.router.super_"></a>[function <span class="apidocSignatureSpan">restify.router.</span>super_ ()](#apidoc.element.restify.router.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.router.prototype"></a>[module restify.router.prototype](#apidoc.module.restify.router.prototype)

#### <a name="apidoc.element.restify.router.prototype.find"></a>[function <span class="apidocSignatureSpan">restify.router.prototype.</span>find (req, res, callback)](#apidoc.element.restify.router.prototype.find)
- description and source-code
```javascript
function find(req, res, callback) {
    var candidates = [];
    var ct = req.headers['content-type'] || DEF_CT;
    var cacheKey = req.method + req.url + req.version() + ct;
    var cacheVal;
    var neg;
    var params;
    var r;
    var reverse;
    var routes = this.routes[req.method] || [];
    var typed;
    var versioned;
    var maxV;

    if ((cacheVal = this.cache.get(cacheKey))) {
        res.methods = cacheVal.methods.slice();
        req._matchedVersion = cacheVal.matchedVersion;
        callback(null, cacheVal, shallowCopy(cacheVal.params));
        return;
    }

    for (var i = 0; i < routes.length; i++) {
        try {
            params = matchURL(routes[i].path, req);
        } catch (e) {
            this.log.trace({err: e}, 'error parsing URL');
            callback(new BadRequestError(e.message));
            return;
        }

        if (params === false) {
            continue;
        }

        reverse = this.reverse[routes[i].path.source];

        if (routes[i].types.length && req.isUpload()) {
            candidates.push({
                p: params,
                r: routes[i]
            });
            typed = true;
            continue;
        }

        // GH-283: we want to find the latest version for a given route,
        // not the first one.  However, if neither the client nor
        // server specified any version, we're done, because neither
        // cared
        if (routes[i].versions.length === 0 && req.version() === '*') {
            r = routes[i];
            break;
        }

        if (routes[i].versions.length > 0) {
            candidates.push({
                p: params,
                r: routes[i]
            });
            versioned = true;
        }
    }

    if (!r) {
        // If upload and typed
        if (typed) {
            var _t = ct.split(/\s*,\s*/);
            candidates = candidates.filter(function (c) {
                neg = new Negotiator({
                    headers: {
                        accept: c.r.types.join(', ')
                    }
                });
                var tmp = neg.preferredMediaType(_t);
                return (tmp && tmp.length);
            });

            // Pick the first one in case not versioned
            if (candidates.length) {
                r = candidates[0].r;
                params = candidates[0].p;
            }
        }

        if (versioned) {
            candidates.forEach(function (c) {
                var k = c.r.versions;
                var v = semver.maxSatisfying(k, req.version());

                if (v) {
                    if (!r || semver.gt(v, maxV)) {
                        r = c.r;
                        params = c.p;
                        maxV = v;
                    }
                }
            });
        }
    }

    // In order, we check if the route exists, in which case, we're good.
    // Otherwise we look to see if ver was set to false; that would tell us
    // we indeed did find a matching route (method+url), but the version
    // field didn't line up, so we return bad version.  If no route and no
    // version, we now need to go walk the reverse map and look at whether
    // we should return 405 or 404.  If it was an OPTIONS request, we need
    // to handle this having been a preflight request.
    if (params && r) {
        cacheVal = {
            methods: reverse,
            name: r.name,
            params: params,
            spec: r.spec
        };

        if (versioned) {
            req._matchedVersion = maxV;
            cacheVal.matchedVersion = maxV;
        }

        this.cache.set(cacheKey, cacheVal);
        res.methods = reverse.slice();
        callback(null, cacheVal, shallowCopy(params));
        return;
    }

    if (typed) {
        callback(new UnsupportedMediaTypeError(ct));
        return;
    }

    if (versioned) {
        callback(new InvalidVersionError('%s is not supported by %s %s',
            req.version() || '?',
            req.method,
            req.path()));
        return;
    }

    //Checks if header is in co ...
```
- example usage
```shell
...
Server.prototype._route = function _route(req, res, name, cb) {
    var self = this;

    if (typeof (name) === 'function') {
        cb = name;
        name = null;

        this.router.find(req, res, function onRoute(err, route, ctx) {
var r = route ? route.name : null;

if (err) {
    if (optionsError(err, req, res)) {
        self.emit('after', req, res, err);
    } else {
        emitRouteError(self, req, res, err);
...
```

#### <a name="apidoc.element.restify.router.prototype.get"></a>[function <span class="apidocSignatureSpan">restify.router.prototype.</span>get (name, req, cb)](#apidoc.element.restify.router.prototype.get)
- description and source-code
```javascript
function get(name, req, cb) {
    var params;
    var route = false;
    var routes = this.routes[req.method] || [];

    var routeName = name.replace(/\W/g, '').toLowerCase();

    for (var i = 0; i < routes.length; i++) {
        if (routes[i].name === routeName) {
            route = routes[i];

            try {
                params = matchURL(route.path, req);
            } catch (e) {
                // if we couldn't match the URL, log it out.
                console.log(e);
            }
            break;
        }
    }

    if (route) {
        cb(null, route, params || {});
    } else {
        cb(new InternalError());
    }
}
```
- example usage
```shell
...
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});

server.listen(8080, function () {
  console.log('%s listening at %s', server.name, server.url);
});
...
```

#### <a name="apidoc.element.restify.router.prototype.mount"></a>[function <span class="apidocSignatureSpan">restify.router.prototype.</span>mount (options)](#apidoc.element.restify.router.prototype.mount)
- description and source-code
```javascript
function mount(options) {
    assert.object(options, 'options');
    assert.string(options.method, 'options.method');
    assert.string(options.name, 'options.name');

    var exists;
    var name = options.name;
    var route;
    var routes = this.routes[options.method];
    var self = this;
    var type = options.contentType || self.contentType;
    var versions = options.versions || options.version || self.versions;

    if (type) {
        if (!Array.isArray(type)) {
            type = [type];
        }
        type.filter(function (t) {
            return (t);
        }).sort().join();
    }

    if (versions) {
        if (!Array.isArray(versions)) {
            versions = [versions];
        }
        versions.sort();
    }

    exists = routes.some(function (r) {
        return (r.name === name);
    });

    if (exists) {
        return (false);
    }

    route = {
        name: name,
        method: options.method,
        path: compileURL({
            url: options.path || options.url,
            flags: options.flags,
            urlParamPattern: options.urlParamPattern
        }),
        spec: options,
        types: type,
        versions: versions
    };
    routes.push(route);

    if (!this.reverse[route.path.source]) {
        this.reverse[route.path.source] = [];
    }

    if (this.reverse[route.path.source].indexOf(route.method) === -1) {
        this.reverse[route.path.source].push(route.method);
    }

    this.mounts[route.name] = route;

    this.emit('mount',
        route.method,
        route.path,
        route.types,
        route.versions);

    return (route.name);
}
```
- example usage
```shell
...
        opts.name += uuid.v4().substr(0, 7);
    }
} else {
    opts.name = opts.name.replace(/\W/g, '').toLowerCase();
}


if (!(route = this.router.mount(opts))) {
    return (false);
}

this.chain.forEach(addHandler);
argumentsToChain(arguments, 1).forEach(addHandler);
this.routes[route] = chain;
...
```

#### <a name="apidoc.element.restify.router.prototype.render"></a>[function <span class="apidocSignatureSpan">restify.router.prototype.</span>render (routeName, params, query)](#apidoc.element.restify.router.prototype.render)
- description and source-code
```javascript
function render(routeName, params, query) {
    function pathItem(match, key) {
        if (params.hasOwnProperty(key) === false) {
            throw new Error('Route <' + routeName +
                            '> is missing parameter <' +
                            key + '>');
        }
        return ('/' + encodeURIComponent(params[key]));
    }

    function queryItem(key) {
        return (encodeURIComponent(key) + '=' + encodeURIComponent(query[key]));
    }

    var routeKey = routeName.replace(/\W/g, '').toLowerCase();
    var route = this.mounts[routeKey];

    if (!route) {
        return (null);
    }

    var _path = route.spec.path;
    var _url = _path.replace(/\/:([A-Za-z0-9_]+)(\([^\\]+?\))?/g, pathItem);
    var items = Object.keys(query || {}).map(queryItem);
    var queryString = items.length > 0 ? ('?' + items.join('&')) : '';
    return (_url + queryString);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.router.prototype.toString"></a>[function <span class="apidocSignatureSpan">restify.router.prototype.</span>toString ()](#apidoc.element.restify.router.prototype.toString)
- description and source-code
```javascript
function toString() {
    var self = this;
    var str = this.name + ':\n';

    Object.keys(this.routes).forEach(function (k) {
        var routes = self.routes[k].map(function (r) {
            return (r.name);
        });

        str += '\t\t' + k + ': [' + routes.join(', ') + ']\n';
    });

    return (str);
}
```
- example usage
```shell
...
    // Client probes
    // method, url, headers, id
    'client-request': ['char *', 'char *', 'json', 'int'],

    // id, statusCode, headers
    'client-response': ['int', 'int', 'json'],

    // id, Error.toString()
    'client-error': ['id', 'char *']
};
var PROVIDER;


///--- API
...
```

#### <a name="apidoc.element.restify.router.prototype.unmount"></a>[function <span class="apidocSignatureSpan">restify.router.prototype.</span>unmount (name)](#apidoc.element.restify.router.prototype.unmount)
- description and source-code
```javascript
function unmount(name) {
    var route = this.mounts[name];

    if (!route) {
        this.log.warn('router.unmount(%s): route does not exist', name);
        return (false);
    }

    var reverse = this.reverse[route.path.source];
    var routes = this.routes[route.method];
    this.routes[route.method] = routes.filter(function (r) {
        return (r.name !== route.name);
    });

    this.reverse[route.path.source] = reverse.filter(function (r) {
        return (r !== route.method);
    });

    if (this.reverse[route.path.source].length === 0) {
        delete this.reverse[route.path.source];
    }

    delete this.mounts[name];

    return (name);
}
```
- example usage
```shell
...
 * @param    {String} name the route name
 * @returns  {String}      the name of the deleted route.
 */
Router.prototype.unmount = function unmount(name) {
var route = this.mounts[name];

if (!route) {
    this.log.warn('router.unmount(%s): route does not exist', name);
    return (false);
}

var reverse = this.reverse[route.path.source];
var routes = this.routes[route.method];
this.routes[route.method] = routes.filter(function (r) {
    return (r.name !== route.name);
...
```



# <a name="apidoc.module.restify.server"></a>[module restify.server](#apidoc.module.restify.server)

#### <a name="apidoc.element.restify.server.server"></a>[function <span class="apidocSignatureSpan">restify.</span>server (options)](#apidoc.element.restify.server.server)
- description and source-code
```javascript
function Server(options) {
    assert.object(options, 'options');
    assert.object(options.log, 'options.log');
    assert.object(options.router, 'options.router');

    var self = this;

    EventEmitter.call(this);

    this.before = [];
    this.chain = [];
    this.log = options.log;
    this.name = options.name || 'restify';
    this.router = options.router;
    this.routes = {};
    this.secure = false;
    this.versions = options.versions || options.version || [];
    this.socketio = options.socketio || false;

    var fmt = mergeFormatters(options.formatters);
    this.acceptable = fmt.acceptable;
    this.formatters = fmt.formatters;

    if (options.hasOwnProperty('handleUncaughtExceptions')) {
        this.handleUncaughtExceptions = options.handleUncaughtExceptions;
    } else {
        this.handleUncaughtExceptions = true;
    }

    if (options.spdy) {
        this.spdy = true;
        this.server = spdy.createServer(options.spdy);
    } else if ((options.cert || options.certificate) && options.key) {
        this.ca = options.ca;
        this.certificate = options.certificate || options.cert;
        this.key = options.key;
        this.passphrase = options.passphrase || null;
        this.secure = true;

        this.server = https.createServer({
            ca: self.ca,
            cert: self.certificate,
            key: self.key,
            passphrase: self.passphrase,
            rejectUnauthorized: options.rejectUnauthorized,
            requestCert: options.requestCert,
            ciphers: options.ciphers
        });
    } else if (options.httpsServerOptions) {
        this.server = https.createServer(options.httpsServerOptions);
    } else {
        this.server = http.createServer();
    }

    this.router.on('mount', this.emit.bind(this, 'mount'));

    if (!options.handleUpgrades && PROXY_EVENTS.indexOf('upgrade') === -1) {
        PROXY_EVENTS.push('upgrade');
    }
    PROXY_EVENTS.forEach(function (e) {
        self.server.on(e, self.emit.bind(self, e));
    });

    // Now the things we can't blindly proxy
    this.server.on('checkContinue', function onCheckContinue(req, res) {
        if (self.listeners('checkContinue').length > 0) {
            self.emit('checkContinue', req, res);
            return;
        }

        if (!options.noWriteContinue) {
            res.writeContinue();
        }

        self._setupRequest(req, res);
        self._handle(req, res, true);
    });

    if (options.handleUpgrades) {
        this.server.on('upgrade', function onUpgrade(req, socket, head) {
            req._upgradeRequest = true;
            var res = upgrade.createResponse(req, socket, head);
            self._setupRequest(req, res);
            self._handle(req, res);
        });
    }

    this.server.on('request', function onRequest(req, res) {
        self.emit('request', req, res);

        if (options.socketio && (/^\/socket\.io.*/).test(req.url)) {
            return;
        }

        self._setupRequest(req, res);
        self._handle(req, res);
    });

    this.__defineGetter__('maxHeadersCount', function () {
        return (self.server.maxHeadersCount);
    });

    this.__defineSetter__('maxHeadersCount', function (c) {
        self.server.maxHeadersCount = c;
        return (c);
    });

    this.__defineGetter__('url', function () {
        if (self.socketPath) {
            return ('http://' + self.socketPath);
        }

        var addr = self.address();
        var str = '';

        if (self.spdy) {
            str += 'spdy://';
        } else if (self.secure) {
            str += 'https://';
        } else {
            str += 'http://';
        }

        if (addr) {
            str += addr.family === 'IPv6' ?
                '[' + addr.address + ']' : addr.address;
            str += ':';
            str += addr.port;
        } else {
            str += '169.254.0.1:0000';
        }

        return (str);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.server.super_"></a>[function <span class="apidocSignatureSpan">restify.server.</span>super_ ()](#apidoc.element.restify.server.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.restify.server.prototype"></a>[module restify.server.prototype](#apidoc.module.restify.server.prototype)

#### <a name="apidoc.element.restify.server.prototype._handle"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>_handle (req, res)](#apidoc.element.restify.server.prototype._handle)
- description and source-code
```javascript
function _handle(req, res) {
    var self = this;

    function routeAndRun() {
        self._route(req, res, function (route, context) {
            req.context = req.params = context;
            req.route = route.spec;

            var r = route ? route.name : null;
            var chain = self.routes[r];

            self._run(req, res, route, chain, function done(e) {
                self.emit('after', req, res, route, e);
            });
        });
    }

    if (this.before.length > 0) {
        this._run(req, res, null, this.before, function (err) {
            if (!err) {
                routeAndRun();
            }
        });
    } else {
        routeAndRun();
    }
}
```
- example usage
```shell
...
    }

    if (!options.noWriteContinue) {
        res.writeContinue();
    }

    self._setupRequest(req, res);
    self._handle(req, res, true);
});

if (options.handleUpgrades) {
    this.server.on('upgrade', function onUpgrade(req, socket, head) {
        req._upgradeRequest = true;
        var res = upgrade.createResponse(req, socket, head);
        self._setupRequest(req, res);
...
```

#### <a name="apidoc.element.restify.server.prototype._route"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>_route (req, res, name, cb)](#apidoc.element.restify.server.prototype._route)
- description and source-code
```javascript
function _route(req, res, name, cb) {
    var self = this;

    if (typeof (name) === 'function') {
        cb = name;
        name = null;

        this.router.find(req, res, function onRoute(err, route, ctx) {
            var r = route ? route.name : null;

            if (err) {
                if (optionsError(err, req, res)) {
                    self.emit('after', req, res, err);
                } else {
                    emitRouteError(self, req, res, err);
                }
            } else if (r === 'preflight') {
                res.writeHead(200);
                res.end();
                self.emit('after', req, res, null);
            } else if (!r || !self.routes[r]) {
                err = new ResourceNotFoundError(req.path());
                emitRouteError(self, res, res, err);
            } else {
                cb(route, ctx);
            }
        });
    } else {
        this.router.get(name, req, function (err, route, ctx) {
            if (err) {
                emitRouteError(self, req, res, err);
            } else {
                cb(route, ctx);
            }
        });
    }
}
```
- example usage
```shell
...
 * @param    {Object} res the response object
 * @returns  {undefined}
 */
Server.prototype._handle = function _handle(req, res) {
    var self = this;

    function routeAndRun() {
        self._route(req, res, function (route, context) {
req.context = req.params = context;
req.route = route.spec;

var r = route ? route.name : null;
var chain = self.routes[r];

self._run(req, res, route, chain, function done(e) {
...
```

#### <a name="apidoc.element.restify.server.prototype._run"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>_run (req, res, route, chain, cb)](#apidoc.element.restify.server.prototype._run)
- description and source-code
```javascript
function _run(req, res, route, chain, cb) {
    var d;
    var i = -1;
    var id = dtrace.nextId();
    req._dtraceId = id;

    if (!req._anonFuncCount) {
        // Counter used to keep track of anonymous functions. Used when a
        // handler function is anonymous. This ensures we're using a
        // monotonically increasing int for anonymous handlers through out the
        // the lifetime of this request
        req._anonFuncCount = 0;
    }
    var log = this.log;
    var self = this;
    var handlerName = null;
    var errName;
    var emittedError = false;

    if (cb) {
        cb = once(cb);
    }

    function next(arg) {
        var done = false;

        if (arg) {
            if (arg instanceof Error) {
                errName = arg.name.replace(/Error$/, '');
                log.trace({err: arg, errName: errName}, 'next(err=%s)',
                    (arg.name || 'Error'));

                if (self.listeners(errName).length > 0) {
                    self.emit(errName, req, res, arg, once(function () {
                        res.send(arg);
                        return (cb ? cb(arg) : true);
                    }));
                    emittedError = true;
                } else {
                    res.send(arg);
                }
                done = true;
            } else if (typeof (arg) === 'string') { // GH-193, allow redirect
                if (req._rstfy_chained_route) {
                    var _e = new errors.InternalError();
                    log.error({
                        err: _e
                    }, 'Multiple next("chain") calls not ' +
                        'supported');
                    res.send(_e);
                    return (false);
                }

                // Stop running the rest of this route since we're redirecting
                return self._route(req, res, arg, function (r, ctx) {
                    req.context = req.params = ctx;
                    req.route = r.spec;

                    var _c = chain.slice(0, i + 1);

                    function _uniq(fn) {
                        return (_c.indexOf(fn) === -1);
                    }

                    var _routes = self.routes[r.name] || [];
                    var _chain = _routes.filter(_uniq);

                    req._rstfy_chained_route = true;

                    // Need to fire DTrace done for previous handler here too.
                    if ((i + 1) > 0 && chain[i] && !chain[i]._skip) {
                        req.endHandlerTimer(handlerName);
                    }
                    self._run(req, res, r, _chain, cb);
                });
            }
        }

        if (arg === false) {
            done = true;
        }

        // Fire DTrace done for the previous handler.
        if ((i + 1) > 0 && chain[i] && !chain[i]._skip) {
            req.endHandlerTimer(handlerName);
        }

        // Run the next handler up
        if (!done && chain[++i]) {
            if (chain[i]._skip) {
                return (next());
            }

            if (log.trace()) {
                log.trace('running %s', chain[i].name || '?');
            }

            req._currentRoute = (route !== null ? route.name : 'pre');
            handlerName = (chain[i].name ||
                           ('handler-' + req._anonFuncCount++));
            req._currentHandler = handlerName;
            req.startHandlerTimer(handlerName);

            var n = once(next);
            n.ifError = ifError(n);
            return (chain[i].call(self, req, res, n));
        }

        dtrace._rstfy_probes['route-done'].fire(function () {
            return ([
                self.name,
                route !== null ? route.name : 'pre',
                id,
                res.statusCode || 200,
                res.headers()
            ]);
        });

        if (route === null) {
            self.emit('preDone', req, res);
        } else {
            self.emit('done', req, res, route);
        }

        // Don't return cb here if we emit an error since we will cb after the
        // handler fire ...
```
- example usage
```shell
...
    self._route(req, res, function (route, context) {
        req.context = req.params = context;
        req.route = route.spec;

        var r = route ? route.name : null;
        var chain = self.routes[r];

        self._run(req, res, route, chain, function done(e) {
            self.emit('after', req, res, route, e);
        });
    });
}

if (this.before.length > 0) {
    this._run(req, res, null, this.before, function (err) {
...
```

#### <a name="apidoc.element.restify.server.prototype._setupRequest"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>_setupRequest (req, res)](#apidoc.element.restify.server.prototype._setupRequest)
- description and source-code
```javascript
function _setupRequest(req, res) {
    req.log = res.log = this.log;
    req._time = res._time = Date.now();
    req.serverName = this.name;

    res.acceptable = this.acceptable;
    res.formatters = this.formatters;
    res.req = req;
    res.serverName = this.name;
    res.version = this.router.versions[this.router.versions.length - 1];
}
```
- example usage
```shell
...
        return;
    }

    if (!options.noWriteContinue) {
        res.writeContinue();
    }

    self._setupRequest(req, res);
    self._handle(req, res, true);
});

if (options.handleUpgrades) {
    this.server.on('upgrade', function onUpgrade(req, socket, head) {
        req._upgradeRequest = true;
        var res = upgrade.createResponse(req, socket, head);
...
```

#### <a name="apidoc.element.restify.server.prototype.address"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>address ()](#apidoc.element.restify.server.prototype.address)
- description and source-code
```javascript
function address() {
    return (this.server.address());
}
```
- example usage
```shell
...
    });

    this.__defineGetter__('url', function () {
if (self.socketPath) {
    return ('http://' + self.socketPath);
}

var addr = self.address();
var str = '';

if (self.spdy) {
    str += 'spdy://';
} else if (self.secure) {
    str += 'https://';
} else {
...
```

#### <a name="apidoc.element.restify.server.prototype.close"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>close (callback)](#apidoc.element.restify.server.prototype.close)
- description and source-code
```javascript
function close(callback) {
    if (callback) {
        assert.func(callback, 'callback');
    }

    this.server.once('close', function onClose() {
        return (callback ? callback() : false);
    });

    return (this.server.close());
}
```
- example usage
```shell
...
       assert.func(callback, 'callback');
   }

   this.server.once('close', function onClose() {
       return (callback ? callback() : false);
   });

   return (this.server.close());
};


// Register all the routing methods
/**
* Mounts a chain on the given path against this HTTP verb
*
...
```

#### <a name="apidoc.element.restify.server.prototype.del"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>del (opts)](#apidoc.element.restify.server.prototype.del)
- description and source-code
```javascript
del = function (opts) {
    if (opts instanceof RegExp || typeof (opts) === 'string') {
        opts = {
            path: opts
        };
    } else if (typeof (opts) === 'object') {
        opts = shallowCopy(opts);
    } else {
        throw new TypeError('path (string) required');
    }

    if (arguments.length < 2) {
        throw new TypeError('handler (function) required');
    }

    var chain = [];
    var route;
    var self = this;

    function addHandler(h) {
        assert.func(h, 'handler');

        chain.push(h);
    }

    if (method === 'del') {
        method = 'DELETE';
    }

    if (method === 'opts') {
        method = 'OPTIONS';
    }
    opts.method = method.toUpperCase();
    opts.versions = opts.versions || opts.version || self.versions;

    if (!Array.isArray(opts.versions)) {
        opts.versions = [opts.versions];
    }

    if (!opts.name) {
        opts.name = method + '-' + (opts.path || opts.url);

        if (opts.versions.length > 0) {
            opts.name += '-' + opts.versions.join('--');
        }

        opts.name = opts.name.replace(/\W/g, '').toLowerCase();

        if (this.router.mounts[opts.name]) { // GH-401
            opts.name += uuid.v4().substr(0, 7);
        }
    } else {
        opts.name = opts.name.replace(/\W/g, '').toLowerCase();
    }


    if (!(route = this.router.mount(opts))) {
        return (false);
    }

    this.chain.forEach(addHandler);
    argumentsToChain(arguments, 1).forEach(addHandler);
    this.routes[route] = chain;

    return (route);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.server.prototype.get"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>get (opts)](#apidoc.element.restify.server.prototype.get)
- description and source-code
```javascript
get = function (opts) {
    if (opts instanceof RegExp || typeof (opts) === 'string') {
        opts = {
            path: opts
        };
    } else if (typeof (opts) === 'object') {
        opts = shallowCopy(opts);
    } else {
        throw new TypeError('path (string) required');
    }

    if (arguments.length < 2) {
        throw new TypeError('handler (function) required');
    }

    var chain = [];
    var route;
    var self = this;

    function addHandler(h) {
        assert.func(h, 'handler');

        chain.push(h);
    }

    if (method === 'del') {
        method = 'DELETE';
    }

    if (method === 'opts') {
        method = 'OPTIONS';
    }
    opts.method = method.toUpperCase();
    opts.versions = opts.versions || opts.version || self.versions;

    if (!Array.isArray(opts.versions)) {
        opts.versions = [opts.versions];
    }

    if (!opts.name) {
        opts.name = method + '-' + (opts.path || opts.url);

        if (opts.versions.length > 0) {
            opts.name += '-' + opts.versions.join('--');
        }

        opts.name = opts.name.replace(/\W/g, '').toLowerCase();

        if (this.router.mounts[opts.name]) { // GH-401
            opts.name += uuid.v4().substr(0, 7);
        }
    } else {
        opts.name = opts.name.replace(/\W/g, '').toLowerCase();
    }


    if (!(route = this.router.mount(opts))) {
        return (false);
    }

    this.chain.forEach(addHandler);
    argumentsToChain(arguments, 1).forEach(addHandler);
    this.routes[route] = chain;

    return (route);
}
```
- example usage
```shell
...
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});

server.listen(8080, function () {
  console.log('%s listening at %s', server.name, server.url);
});
...
```

#### <a name="apidoc.element.restify.server.prototype.head"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>head (opts)](#apidoc.element.restify.server.prototype.head)
- description and source-code
```javascript
head = function (opts) {
    if (opts instanceof RegExp || typeof (opts) === 'string') {
        opts = {
            path: opts
        };
    } else if (typeof (opts) === 'object') {
        opts = shallowCopy(opts);
    } else {
        throw new TypeError('path (string) required');
    }

    if (arguments.length < 2) {
        throw new TypeError('handler (function) required');
    }

    var chain = [];
    var route;
    var self = this;

    function addHandler(h) {
        assert.func(h, 'handler');

        chain.push(h);
    }

    if (method === 'del') {
        method = 'DELETE';
    }

    if (method === 'opts') {
        method = 'OPTIONS';
    }
    opts.method = method.toUpperCase();
    opts.versions = opts.versions || opts.version || self.versions;

    if (!Array.isArray(opts.versions)) {
        opts.versions = [opts.versions];
    }

    if (!opts.name) {
        opts.name = method + '-' + (opts.path || opts.url);

        if (opts.versions.length > 0) {
            opts.name += '-' + opts.versions.join('--');
        }

        opts.name = opts.name.replace(/\W/g, '').toLowerCase();

        if (this.router.mounts[opts.name]) { // GH-401
            opts.name += uuid.v4().substr(0, 7);
        }
    } else {
        opts.name = opts.name.replace(/\W/g, '').toLowerCase();
    }


    if (!(route = this.router.mount(opts))) {
        return (false);
    }

    this.chain.forEach(addHandler);
    argumentsToChain(arguments, 1).forEach(addHandler);
    this.routes[route] = chain;

    return (route);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.server.prototype.listen"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>listen ()](#apidoc.element.restify.server.prototype.listen)
- description and source-code
```javascript
function listen() {
    var args = Array.prototype.slice.call(arguments);
    return (this.server.listen.apply(this.server, args));
}
```
- example usage
```shell
...
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});

server.listen(8080, function () {
  console.log('%s listening at %s', server.name, server.url);
});
'''

## Client

'''javascript
...
```

#### <a name="apidoc.element.restify.server.prototype.opts"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>opts (opts)](#apidoc.element.restify.server.prototype.opts)
- description and source-code
```javascript
opts = function (opts) {
    if (opts instanceof RegExp || typeof (opts) === 'string') {
        opts = {
            path: opts
        };
    } else if (typeof (opts) === 'object') {
        opts = shallowCopy(opts);
    } else {
        throw new TypeError('path (string) required');
    }

    if (arguments.length < 2) {
        throw new TypeError('handler (function) required');
    }

    var chain = [];
    var route;
    var self = this;

    function addHandler(h) {
        assert.func(h, 'handler');

        chain.push(h);
    }

    if (method === 'del') {
        method = 'DELETE';
    }

    if (method === 'opts') {
        method = 'OPTIONS';
    }
    opts.method = method.toUpperCase();
    opts.versions = opts.versions || opts.version || self.versions;

    if (!Array.isArray(opts.versions)) {
        opts.versions = [opts.versions];
    }

    if (!opts.name) {
        opts.name = method + '-' + (opts.path || opts.url);

        if (opts.versions.length > 0) {
            opts.name += '-' + opts.versions.join('--');
        }

        opts.name = opts.name.replace(/\W/g, '').toLowerCase();

        if (this.router.mounts[opts.name]) { // GH-401
            opts.name += uuid.v4().substr(0, 7);
        }
    } else {
        opts.name = opts.name.replace(/\W/g, '').toLowerCase();
    }


    if (!(route = this.router.mount(opts))) {
        return (false);
    }

    this.chain.forEach(addHandler);
    argumentsToChain(arguments, 1).forEach(addHandler);
    this.routes[route] = chain;

    return (route);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.server.prototype.param"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>param (name, fn)](#apidoc.element.restify.server.prototype.param)
- description and source-code
```javascript
function param(name, fn) {
    this.use(function _param(req, res, next) {
        if (req.params && req.params[name]) {
            fn.call(this, req, res, next, req.params[name], name);
        } else {
            next();
        }
    });

    return (this);
}
```
- example usage
```shell
...
* @link http://expressjs.com/guide.html#route-param%20pre-conditions
*
* This basically piggy-backs on the 'server.use' method. It attaches a
* new middleware function that only fires if the specified parameter exists
* in req.params
*
* Exposes an API:
*   server.param("user", function (req, res, next) {
*     // load the user's information here, always making sure to call next()
*   });
*
* @public
* @function param
* @param    {String}   name The name of the URL param to respond to
* @param    {Function} fn   The middleware function to execute
...
```

#### <a name="apidoc.element.restify.server.prototype.patch"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>patch (opts)](#apidoc.element.restify.server.prototype.patch)
- description and source-code
```javascript
patch = function (opts) {
    if (opts instanceof RegExp || typeof (opts) === 'string') {
        opts = {
            path: opts
        };
    } else if (typeof (opts) === 'object') {
        opts = shallowCopy(opts);
    } else {
        throw new TypeError('path (string) required');
    }

    if (arguments.length < 2) {
        throw new TypeError('handler (function) required');
    }

    var chain = [];
    var route;
    var self = this;

    function addHandler(h) {
        assert.func(h, 'handler');

        chain.push(h);
    }

    if (method === 'del') {
        method = 'DELETE';
    }

    if (method === 'opts') {
        method = 'OPTIONS';
    }
    opts.method = method.toUpperCase();
    opts.versions = opts.versions || opts.version || self.versions;

    if (!Array.isArray(opts.versions)) {
        opts.versions = [opts.versions];
    }

    if (!opts.name) {
        opts.name = method + '-' + (opts.path || opts.url);

        if (opts.versions.length > 0) {
            opts.name += '-' + opts.versions.join('--');
        }

        opts.name = opts.name.replace(/\W/g, '').toLowerCase();

        if (this.router.mounts[opts.name]) { // GH-401
            opts.name += uuid.v4().substr(0, 7);
        }
    } else {
        opts.name = opts.name.replace(/\W/g, '').toLowerCase();
    }


    if (!(route = this.router.mount(opts))) {
        return (false);
    }

    this.chain.forEach(addHandler);
    argumentsToChain(arguments, 1).forEach(addHandler);
    this.routes[route] = chain;

    return (route);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.server.prototype.post"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>post (opts)](#apidoc.element.restify.server.prototype.post)
- description and source-code
```javascript
post = function (opts) {
    if (opts instanceof RegExp || typeof (opts) === 'string') {
        opts = {
            path: opts
        };
    } else if (typeof (opts) === 'object') {
        opts = shallowCopy(opts);
    } else {
        throw new TypeError('path (string) required');
    }

    if (arguments.length < 2) {
        throw new TypeError('handler (function) required');
    }

    var chain = [];
    var route;
    var self = this;

    function addHandler(h) {
        assert.func(h, 'handler');

        chain.push(h);
    }

    if (method === 'del') {
        method = 'DELETE';
    }

    if (method === 'opts') {
        method = 'OPTIONS';
    }
    opts.method = method.toUpperCase();
    opts.versions = opts.versions || opts.version || self.versions;

    if (!Array.isArray(opts.versions)) {
        opts.versions = [opts.versions];
    }

    if (!opts.name) {
        opts.name = method + '-' + (opts.path || opts.url);

        if (opts.versions.length > 0) {
            opts.name += '-' + opts.versions.join('--');
        }

        opts.name = opts.name.replace(/\W/g, '').toLowerCase();

        if (this.router.mounts[opts.name]) { // GH-401
            opts.name += uuid.v4().substr(0, 7);
        }
    } else {
        opts.name = opts.name.replace(/\W/g, '').toLowerCase();
    }


    if (!(route = this.router.mount(opts))) {
        return (false);
    }

    this.chain.forEach(addHandler);
    argumentsToChain(arguments, 1).forEach(addHandler);
    this.routes[route] = chain;

    return (route);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.server.prototype.pre"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>pre ()](#apidoc.element.restify.server.prototype.pre)
- description and source-code
```javascript
function pre() {
    var self = this;

    argumentsToChain(arguments).forEach(function (h) {
        self.before.push(h);
    });

    return (this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.server.prototype.put"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>put (opts)](#apidoc.element.restify.server.prototype.put)
- description and source-code
```javascript
put = function (opts) {
    if (opts instanceof RegExp || typeof (opts) === 'string') {
        opts = {
            path: opts
        };
    } else if (typeof (opts) === 'object') {
        opts = shallowCopy(opts);
    } else {
        throw new TypeError('path (string) required');
    }

    if (arguments.length < 2) {
        throw new TypeError('handler (function) required');
    }

    var chain = [];
    var route;
    var self = this;

    function addHandler(h) {
        assert.func(h, 'handler');

        chain.push(h);
    }

    if (method === 'del') {
        method = 'DELETE';
    }

    if (method === 'opts') {
        method = 'OPTIONS';
    }
    opts.method = method.toUpperCase();
    opts.versions = opts.versions || opts.version || self.versions;

    if (!Array.isArray(opts.versions)) {
        opts.versions = [opts.versions];
    }

    if (!opts.name) {
        opts.name = method + '-' + (opts.path || opts.url);

        if (opts.versions.length > 0) {
            opts.name += '-' + opts.versions.join('--');
        }

        opts.name = opts.name.replace(/\W/g, '').toLowerCase();

        if (this.router.mounts[opts.name]) { // GH-401
            opts.name += uuid.v4().substr(0, 7);
        }
    } else {
        opts.name = opts.name.replace(/\W/g, '').toLowerCase();
    }


    if (!(route = this.router.mount(opts))) {
        return (false);
    }

    this.chain.forEach(addHandler);
    argumentsToChain(arguments, 1).forEach(addHandler);
    this.routes[route] = chain;

    return (route);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.server.prototype.rm"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>rm (route)](#apidoc.element.restify.server.prototype.rm)
- description and source-code
```javascript
function rm(route) {
    var r = this.router.unmount(route);

    if (r && this.routes[r]) {
        delete this.routes[r];
    }

    return (r);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.server.prototype.toString"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>toString ()](#apidoc.element.restify.server.prototype.toString)
- description and source-code
```javascript
function toString() {
    var LINE_FMT = '\t%s: %s\n';
    var SUB_LINE_FMT = '\t\t%s: %s\n';
    var self = this;
    var str = '';

    function handlersToString(arr) {
        var s = '[' + arr.map(function (b) {
            return (b.name || 'function');
        }).join(', ') + ']';

        return (s);
    }

    str += sprintf(LINE_FMT, 'Accepts', this.acceptable.join(', '));
    str += sprintf(LINE_FMT, 'Name', this.name);
    str += sprintf(LINE_FMT, 'Pre', handlersToString(this.before));
    str += sprintf(LINE_FMT, 'Router', this.router.toString());
    str += sprintf(LINE_FMT, 'Routes', '');
    Object.keys(this.routes).forEach(function (k) {
        var handlers = handlersToString(self.routes[k]);
        str += sprintf(SUB_LINE_FMT, k, handlers);
    });
    str += sprintf(LINE_FMT, 'Secure', this.secure);
    str += sprintf(LINE_FMT, 'Url', this.url);
    str += sprintf(LINE_FMT, 'Version', Array.isArray(this.versions) ?
                   this.versions.join() :
                   this.versions);

    return (str);
}
```
- example usage
```shell
...
    // Client probes
    // method, url, headers, id
    'client-request': ['char *', 'char *', 'json', 'int'],

    // id, statusCode, headers
    'client-response': ['int', 'int', 'json'],

    // id, Error.toString()
    'client-error': ['id', 'char *']
};
var PROVIDER;


///--- API
...
```

#### <a name="apidoc.element.restify.server.prototype.use"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>use ()](#apidoc.element.restify.server.prototype.use)
- description and source-code
```javascript
function use() {
    var self = this;

    (argumentsToChain(arguments) || []).forEach(function (h) {
        self.chain.push(h);
    });

    return (this);
}
```
- example usage
```shell
...
'''javascript
var restify = require('restify');

var server = restify.createServer({
  name: 'myapp',
  version: '1.0.0'
});
server.use(restify.acceptParser(server.acceptable));
server.use(restify.queryParser());
server.use(restify.bodyParser());

server.get('/echo/:name', function (req, res, next) {
  res.send(req.params);
  return next();
});
...
```

#### <a name="apidoc.element.restify.server.prototype.versionedUse"></a>[function <span class="apidocSignatureSpan">restify.server.prototype.</span>versionedUse (versions, fn)](#apidoc.element.restify.server.prototype.versionedUse)
- description and source-code
```javascript
function versionedUse(versions, fn) {
    if (!Array.isArray(versions)) {
        versions = [versions];
    }
    assert.arrayOfString(versions, 'versions');

    versions.forEach(function (v) {
        if (!semver.valid(v)) {
            throw new TypeError('%s is not a valid semver', v);
        }
    });

    this.use(function _versionedUse(req, res, next) {
        var ver;

        if (req.version() === '*' ||
            (ver = maxSatisfying(versions,
                req.version()) || false)) {
            fn.call(this, req, res, next, ver);
        } else {
            next();
        }
    });

    return (this);
}
```
- example usage
```shell
...
* function that only fires if the specified version matchtes the request.
*
* Note that if the client does not request a specific version, the middleware
* function always fires. If you don't want this set a default version with a
* pre handler on requests where the client omits one.
*
* Exposes an API:
*   server.versionedUse("version", function (req, res, next, ver) {
*     // do stuff that only applies to routes of this API version
*   });
*
* @public
* @function versionedUse
* @param    {String|Array} versions the version(s) the URL to respond to
* @param    {Function}     fn       the middleware function to execute, the
...
```



# <a name="apidoc.module.restify.upgrade"></a>[module restify.upgrade](#apidoc.module.restify.upgrade)

#### <a name="apidoc.element.restify.upgrade.InvalidUpgradeStateError"></a>[function <span class="apidocSignatureSpan">restify.upgrade.</span>InvalidUpgradeStateError (msg)](#apidoc.element.restify.upgrade.InvalidUpgradeStateError)
- description and source-code
```javascript
function InvalidUpgradeStateError(msg) {
    if (Error.captureStackTrace) {
        Error.captureStackTrace(this, InvalidUpgradeStateError);
    }

    this.message = msg;
    this.name = 'InvalidUpgradeStateError';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.upgrade.createResponse"></a>[function <span class="apidocSignatureSpan">restify.upgrade.</span>createResponse (req, socket, head)](#apidoc.element.restify.upgrade.createResponse)
- description and source-code
```javascript
function createServerUpgradeResponse(req, socket, head) {
    return (new ServerUpgradeResponse(socket, head));
}
```
- example usage
```shell
...
    self._setupRequest(req, res);
    self._handle(req, res, true);
});

if (options.handleUpgrades) {
    this.server.on('upgrade', function onUpgrade(req, socket, head) {
        req._upgradeRequest = true;
        var res = upgrade.createResponse(req, socket, head);
        self._setupRequest(req, res);
        self._handle(req, res);
    });
}

this.server.on('request', function onRequest(req, res) {
    self.emit('request', req, res);
...
```



# <a name="apidoc.module.restify.utils"></a>[module restify.utils](#apidoc.module.restify.utils)

#### <a name="apidoc.element.restify.utils.mergeQs"></a>[function <span class="apidocSignatureSpan">restify.utils.</span>mergeQs (obj1, obj2)](#apidoc.element.restify.utils.mergeQs)
- description and source-code
```javascript
function mergeQs(obj1, obj2) {

    var merged = shallowCopy(obj1) || {};

    // defend against null cause null is an object. yay js.
    if (obj2 && typeof (obj2) === 'object') {
        Object.keys(obj2).forEach(function (key) {
            // if we already have this key and it isn't an array,
            // make it one array of the same element.
            if (merged.hasOwnProperty(key) && !(merged[key] instanceof Array)) {
                merged[key] = [merged[key]];

                // push the new value down
                merged[key].push(obj2[key]);
            } else {
                // otherwise just set it
                merged[key] = obj2[key];
            }
        });
    }

    return (merged);
}
```
- example usage
```shell
...
}

// then add query params
if (opt.query) {
    if (opt.overrideQuery === true) {
        finalUri.query = opt.query;
    } else {
        finalUri.query = utils.mergeQs(opt.query, finalUri.query);
    }
}

// change status code to 301 permanent if specified
if (opt.permanent) {
    statusCode = 301;
}
...
```

#### <a name="apidoc.element.restify.utils.sanitizePath"></a>[function <span class="apidocSignatureSpan">restify.utils.</span>sanitizePath (path)](#apidoc.element.restify.utils.sanitizePath)
- description and source-code
```javascript
function sanitizePath(path) {
    assert.ok(path);

    // Be nice like apache and strip out any //my//foo//bar///blah
    path = path.replace(/\/\/+/g, '/');

    // Kill a trailing '/'
    if (path.lastIndexOf('/') === (path.length - 1) && path.length > 1) {
        path = path.substr(0, path.length - 1);
    }

    return (path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.restify.utils.shallowCopy"></a>[function <span class="apidocSignatureSpan">restify.utils.</span>shallowCopy (obj)](#apidoc.element.restify.utils.shallowCopy)
- description and source-code
```javascript
function shallowCopy(obj) {
    if (!obj) {
        return (obj);
    }
    var copy = {};
    Object.keys(obj).forEach(function (k) {
        copy[k] = obj[k];
    });
    return (copy);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

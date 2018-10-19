curl-to-Go
===========

[![GuardRails badge](https://badges.production.guardrails.io/moul/curl-to-go.svg)](https://www.guardrails.io)

curl-to-Go is a tool to instantly convert [curl](http://curl.haxx.se) commands to Go code in the browser. It does *not* guarantee high-fidelity conversions, but it's good enough for most API docs that have curl samples.

This is a sister tool to [JSON-to-Go](https://mholt.github.io/json-to-go), which converts JSON to a Go struct type definition.


### Try it

**[Check it out!](https://mholt.github.io/curl-to-go)** It works inside your browser. Just give the code a once-over since it will need you to flush out some parts like error handling.


### FAQ

#### Does any curl command work?

Any curl command should work, but only certain flags are understood and converted into Go code. The rest of the flags will be ignored.

#### Which kinds of curl commands are understood?

Mostly simple HTTP commands (headers, basic auth, body, etc).

#### Will you consider supporting *this-or-that* flag?

curl has like a bajillion options, so don't expect all of them to be implemented; just the most common/important ones to stub out code from API samples and docs, etc. But feel free to open an issue or submit a pull request!



### Credits

curl-to-Go is brought to you by Matt Holt ([mholt6](https://twitter.com/mholt6)). Enjoy!

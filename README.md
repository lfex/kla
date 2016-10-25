# klä

[![Build Status][travis badge]][travis] [![LFE Versions][lfe badge]][lfe] [![Erlang Versions][erlang badge]][versions] [![Tags][github tags badge]][github tags] [![Downloads][hex downloads]][hex package]

[![][kla-logo]][kla-logo-large]

*An LFE Wrapper Library used to Dress Up Erlang Libraries in a Lispy Costume*


##### Contents

* [Introduction](#introduction-)
* [Dependencies](#dependencies-)
* [Installation](#installation-)
* [Usage](#usage-)


## Introduction [&#x219F;](#contents)

Add content to me here!


## Dependencies [&#x219F;](#contents)

As of version 0.5.0, this project assumes that you have
[rebar3](https://github.com/rebar/rebar3) installed somwhere in your ``$PATH``.
It no longer uses the old version of rebar. If you do not wish to use rebar3,
you may use the most recent rebar2-compatible release of kla: 0.4.2.


## Installation [&#x219F;](#contents)

Just add it to your ``rebar.config`` deps:

```erlang
  {deps, [
    ...
    {kla, ".*",
      {git, "git@github.com:lfex/kla.git", {tag, "0.5.0"}}}
      ]}.
```

And then do the usual:

```bash
    $ rebar get-deps
    $ rebar compile
```


## Usage [&#x219F;](#contents)

Add content to me here!



<!-- Named page links below: /-->

[kla-logo]: priv/images/vikings-small.png
[kla-logo-large]: http://callego.deviantart.com/art/Viking-Clothes-334955145
[github]: https://github.com/lfex/kla
[gitlab]: https://gitlab.com/lfex/kla
[travis]: https://travis-ci.org/lfex/kla
[travis badge]: https://img.shields.io/travis/lfex/kla.svg
[lfe]: https://github.com/rvirding/lfe
[lfe badge]: https://img.shields.io/badge/lfe-1.2.0-blue.svg
[erlang badge]: https://img.shields.io/badge/erlang-R15%20to%2019.1-blue.svg
[versions]: https://github.com/lfex/kla/blob/master/.travis.yml
[github tags]: https://github.com/lfex/kla/tags
[github tags badge]: https://img.shields.io/github/tag/lfex/kla.svg
[github downloads]: https://img.shields.io/github/downloads/atom/atom/total.svg
[hex badge]: https://img.shields.io/hexpm/v/kla.svg?maxAge=2592000
[hex package]: https://hex.pm/packages/kla
[hex downloads]: https://img.shields.io/hexpm/dt/kla.svg


termcap
=====

An pure erlang termcap library

Build
-----

```
$ rebar3 compile
```

Usage
-----

To get a proplist of the terminal capabilities:
```erlang
termcap:cap("xterm").
```
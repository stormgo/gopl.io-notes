# gopl.io-notes

See this
[fork of gopl.io]
(https://github.com/stormasm/gopl.io)
in my github.

### Aliases

```
alias gop='export GOPATH=${PWD}; export GOBIN=${PWD}/bin; PATH=$PATH:$GOPATH/bin'
alias gopc='env | grep GOPATH'
alias gr='go run'
alias gtb='go test -bench .'
```

To build all of these programs set your ***GOPATH*** first and then go get something.

### chapter 08

##### cake

    go get gopl.io/ch8/cake
    cd src/gopl.io/ch8/

    cd cake
    gtb

##### chat

    cd chat
    go run chat.go
    telnet localhost 8000

##### crawl2

    cd crawl2
    go get
    gr findlinks.go http://google.com
    gr findlinks.go http://intel.com

##### du4

    cd du4
    gr main.go /tmp

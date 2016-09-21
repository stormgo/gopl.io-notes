# gopl.io-notes

See the fork of gopl.io in my github.

### Aliases

```
alias gop='export GOPATH=${PWD}; export GOBIN=${PWD}/bin; PATH=$PATH:$GOPATH/bin'
alias gopc='env | grep GOPATH'
alias gr='go run'
alias gtb='go test -bench .'
```

To build all of these programs set your $GOPATH first and then go get something.

### chapter 08

go get gopl.io/ch8/cake
cd src/gopl.io/ch8/

cd cake
gtb

cd crawl2
go get
gr findlinks.go http://google.com
gr findlinks.go http://intel.com

# info

*cf plugin for showing current user info*

## installation

```
$ go get github.com/cloudfoundry-community/info
$ cf install-plugin $GOPATH/bin/info
```

## usage

```
$ cf info
```

## sample output
```
Current User Info
User: admin
Org: dev
Space: dev
API Version: 2.18.0
API Endpoint: https://api.10.244.0.34.xip.io
```

## method

**info** prints out current user info

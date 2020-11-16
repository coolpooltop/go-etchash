# go-etchash

Etchash go module intended for use by open-etc-pool (and open-ethereum-pool).

### usage

```go
var ecip1099FBlockClassic uint64 = 11700000 // classic mainnet
var ecip1099FBlockMordor uint64 = 2520000 // mordor testnet

var hasher = etchash.New(&ecip1099FBlockMordor)

if hasher.Verify(block) {
    ...
}
```

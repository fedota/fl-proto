# FL Proto
Protocol Buffer 3 definintions for the gRPC service calls used in Fedota

- `fl-round`: used for communication between [clients](https://github.com/fedota/fl-client) and [selector](https://github.com/fedota/fl-selector)
- `fl-intra`: used for communication between [selector](https://github.com/fedota/fl-selector) and [coordinator](https://github.com/fedota/fl-coordinator)
- `fl-status`: used to get round status updates to [webserver](https://github.com/fedota/fl-webserver) from [coordinator](https://github.com/fedota/fl-coordinator)

### Mods for fl-proto
```
go mod init github.com/fedota/fl-proto

cd fl_status
git mod init github.com/fedota/fl-proto/fl_status
cd ..
git add 
```
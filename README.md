# FL Proto
Protocol Buffer 3 definintions for the gRPC service calls used in Fedota

- `fl_round`: used for communication between [clients](https://github.com/fedota/fl-client) and [selector](https://github.com/fedota/fl-selector)
- `fl_intra`: used for communication between [selector](https://github.com/fedota/fl-selector) and [coordinator](https://github.com/fedota/fl-coordinator)
- `fl_status`: used to get round status updates to [webserver](https://github.com/fedota/fl-webserver) from [coordinator](https://github.com/fedota/fl-coordinator)

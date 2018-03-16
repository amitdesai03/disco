# disco
Distributed compressed cache

Sorry to dissapoint, but this is not working project yet.
Although if you are interested, lets work towards making this.

## Uniquie features

- Saves data in highly compressed form (Using roaring bitmap)
- Usually residing on client host (JSR 107 compliant)
- P2P Incremental replication/sync (Using gossip)
- Leader election on network partition (Using zookeeper)

## Where will it be used?

- IOT devices
- High volume data sets servers


Examples
========

* [Basic](./basic.rs) - Basic client usage.
* [TLS](./tls.rs) - Setting up a client that uses TLS.
* [Globals](./globals.rs) - Read and modify global variables to tune the performance of the clients.
* [Publish-Subscribe](./pubsub.rs) - Use multiple clients together with the pubsub interface in a way that survives network interruptions.
* [Blocking](./blocking.rs) - Use multiple clients with the blocking list interface.
* [Transactions](./transactions.rs) - Use the MULTI/EXEC interface on a client.
* [Pipeline](./pipeline.rs) - Use the manual pipeline interface.
* [Lua](./lua.rs) - Use the Lua scripting interface on a client.
* [Scan](./scan.rs) - Use the SCAN interface to scan and read keys.
* [Pool](./pool.rs) - Use a redis connection pool. 
* [Monitor](./monitor.rs) - Process a `MONITOR` stream.
* [Sentinel](./sentinel.rs) - Connect using a sentinel deployment.
* [Serde JSON](./serde_json.rs) - Use the `serde-json` feature to convert between Redis types and JSON. 
* [Redis JSON](./redis_json.rs) - Use the `redis-json` feature with `serde-json` types.
* [Custom](./custom.rs) - Send custom commands or operate on RESP frames.
* [DNS](./dns.rs) - Customize the DNS resolution logic. 
* [Client Tracking](./client_tracking.rs) - Implement [client side caching](https://redis.io/docs/manual/client-side-caching/). 
* [Events](./events.rs) - Respond to connection events with the `EventsInterface`.
* [Keyspace Notifications](./keyspace.rs) - Use the [keyspace notifications](https://redis.io/docs/manual/keyspace-notifications/) interface.
* [Misc](./misc.rs) - Miscellaneous or advanced features. 

Or see the [tests](../tests/integration) for more examples.
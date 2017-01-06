## Changes on this fork

* Dramatically reduce unnecessary writes (PUT requests) to KV when health check status is unchanged.
* Improve checking against blacklist by reducing the number of calls to KV.
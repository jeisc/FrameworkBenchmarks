# Lithium Benchmarking Test

This test benchmarks the `lithium::http_backend`. It is a modern C++17
asynchronous web server based on epoll.

Author: Matthieu Garrigues <matthieu.garrigues@gmail.com>

### Test Type Implementation Source Code

* [JSON] lithium.cc
* [PLAINTEXT] lithium.cc
* [DB] lithium.cc
* [QUERY] lithium.cc
* [CACHED QUERY] lithium.cc
* [UPDATE] lithium.cc
* [FORTUNES] lithium.cc

## Important Libraries
The tests were run with:
* [The Lithium libraries](https://github.com/matt-42/lithium)

## Test URLs
### JSON

http://localhost:8080/json

### PLAINTEXT

http://localhost:8080/plaintext

### DB

http://localhost:8080/db

### QUERY

http://localhost:8080/query?N=

### UPDATE

http://localhost:8080/update?N=

### FORTUNES

http://localhost:8080/fortunes

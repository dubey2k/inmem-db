# In-Memory Database (inmem-db)

A lightweight, fast, and simple in-memory database designed for rapid data retrieval and manipulation. This project is ideal for applications where performance and low latency are crucial, such as caching, session storage, or temporary data manipulation.

## Features

- **Fast Data Access**: Optimized for speed with in-memory storage.
- **Lightweight**: Minimal dependencies and low memory footprint.
- **Simple API**: Easy-to-use interface for basic CRUD (Create, Read, Update, Delete) operations.
- **Concurrent Access**: Supports multiple concurrent read and write operations.
- **Configurable Persistence**: Option to persist data periodically or on shutdown.

## Installation

To use the `inmem-db` in your project, clone this repository:

```bash
git clone https://github.com/dubey2k/inmem-db.git
cd inmem-db

# Start redis-cli and connect to the server
redis-cli -p 6379
or 
redis-cli

# Check the server
127.0.0.1:6379> PING
PONG

# Set a key-value pair
127.0.0.1:6379> SET mykey "Hello World"
OK

# Get the value of a key
127.0.0.1:6379> GET mykey
"Hello World"

# Get the value of a key
127.0.0.1:6379> GET mykey
"Hello World"

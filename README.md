# ScyllaDB Rust Driver Setup

This repository contains the setup for a ScyllaDB session using the Scylla Rust driver. It includes the creation of a new keyspace and table, along with basic CRUD operations: inserting a value and querying rows from the table. The connection to ScyllaDB is configurable via the SCYLLA_URI environment variable, defaulting to localhost.

## Features

- Establish ScyllaDB session with configurable URI
- Create keyspace and table if they do not exist
- Implement insert and query operations for basic data interaction

## Getting Started

To get started with this ScyllaDB Rust driver setup, follow these steps:

1. Clone the repository: `git clone https://github.com/mranv/scylla`
2. Set the SCYLLA_URI environment variable to configure the ScyllaDB connection. If not set, it will default to localhost.
3. Build and run the application.

## Usage

Once the setup is complete, you can use the ScyllaDB Rust driver for basic data interaction with ScyllaDB. The provided code includes examples of inserting a value and querying rows from the table.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request.


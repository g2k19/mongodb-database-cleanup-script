# MongoDB Database Cleanup Script

A simple Node.js script that drops all collections from specified MongoDB databases. Perfect for cleaning demo environments, test databases, or any scenario where you need a fresh start.

## What it does

- Connects to each specified database
- Finds all collections in each database
- Drops each collection completely (documents, indexes, and structure)


# journalioMigration

Groovy script that migrates Jornal.IO logs between versions.

Currently it supports migration from 1.2 format version to 1.3 format.

Script migrates logs recursive. It does it paraller in 5 threads. To change this number, modify POOL_SIZE value.

## Dependencies

Script was tested with Groovy v. 1.8.6.

## Usage

./journalioMigration oldLogsRoot newLogsRoot

## About

More about Journal.IO project you can find on: https://github.com/sbtourist/Journal.IO

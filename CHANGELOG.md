# Changelog

## 0.1.6

- Bugfix: RespClient hangs when pipelining commands

## 0.1.5

- Added list commands (LPUSH, LPOP, etc.)

## 0.1.4

- Added hash commands (HSET, HGET, etc.)

## 0.1.3

- Added AUTH command

## 0.1.2

- Bugfix: Fixed handling of null bulk strings and arrays in deserialization.
- Added SELECT, FLUSHDB and FLUSHALL commands.
- Cleaned up dependencies.
- Changed Dart SDK constraint to Dart 2 stable. 

## 0.1.1

- Added PEXPIRE command. 

## 0.1.0

- Initial version

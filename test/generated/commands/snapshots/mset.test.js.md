# Snapshot report for `test\generated\commands\mset.test.js`

The actual snapshot is saved in `mset.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/mset.md example 1

> Snapshot 1

    [
      'await handy.mset(["key1", "Hello"], ["key2", "World"])  => "OK"',
      'await handy.get("key1")                                 => "Hello"',
      'await handy.get("key2")                                 => "World"',
    ]
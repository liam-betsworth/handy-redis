# Snapshot report for `test\generated\commands\ltrim.test.js`

The actual snapshot is saved in `ltrim.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/ltrim.md example 1

> Snapshot 1

    [
      'await handy.rpush("mylist", "one")    => 1',
      'await handy.rpush("mylist", "two")    => 2',
      'await handy.rpush("mylist", "three")  => 3',
      'await handy.ltrim("mylist", 1, -1)    => "OK"',
      'await handy.lrange("mylist", 0, -1)   => ["two","three"]',
    ]

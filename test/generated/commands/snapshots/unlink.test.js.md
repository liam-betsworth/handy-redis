# Snapshot report for `test\generated\commands\unlink.test.js`

The actual snapshot is saved in `unlink.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/unlink.md example 1

> Snapshot 1

    {
      _commands: [
        'await handy.set("key1", "Hello")',
        'await handy.set("key2", "World")',
        'await handy.unlink("key1", "key2", "key3")',
      ],
      _output: [
        'OK',
        'OK',
      ],
      err: ReplyError {
        args: [
          'key1',
          'key2',
          'key3',
        ],
        code: 'ERR',
        command: 'UNLINK',
      },
    }
# Snapshot report for `test\generated\commands\georadiusbymember.test.js`

The actual snapshot is saved in `georadiusbymember.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/georadiusbymember.md example 1

> Snapshot 1

    [
      'await handy.geoadd("Sicily", [13.583333, 37.316667, "Agrigento"])                                   => 1',
      'await handy.geoadd("Sicily", [13.361389, 38.115556, "Palermo"], [15.087269, 37.502669, "Catania"])  => 2',
      'await handy.georadiusbymember("Sicily", "Agrigento", 100, "km")                                     => ["Agrigento","Palermo"]',
    ]

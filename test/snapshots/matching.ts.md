# Snapshot report for `test/matching.ts`

The actual snapshot is saved in `matching.ts.snap`.

Generated by [AVA](https://ava.li).

## exact match multiple keys

> Snapshot 1

    [
      {
        subtitle: 'foo bar',
        title: 'Foo',
      },
      {
        subtitle: 'ploop',
        title: 'Foo bar',
      },
      {
        subtitle: 'foo bar bleep',
        title: 'Bar',
      },
      {
        match: 'Abra',
        subtitle: 'eep foo blep',
        title: 'Eep',
      },
    ]

## no query should return all items

> Snapshot 1

    [
      {
        subtitle: 'foo bar',
        title: 'Foo',
      },
      {
        subtitle: 'foo bar bleep',
        title: 'Bar',
      },
      {
        match: 'Abra',
        subtitle: 'eep foo blep',
        title: 'Eep',
      },
      {
        subtitle: 'ploop',
        title: 'Foo bar',
      },
      {
        subtitle: 'cadabra',
        title: 'Abra',
      },
    ]

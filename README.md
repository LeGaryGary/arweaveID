# ArweaveID
An identity registry for Arweave addresses

To fetch an Arweave address' identity (ArQL):
```
{
    op: 'and',
    expr1:
        {
            op: 'equals',
            expr1: 'App-Name',
            expr2: 'arweave-id'
        },
    expr2:
        {
            op: 'equals',
            expr1: 'from',
            expr2: [target_address],
        },
  }
```

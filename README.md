# binstrument

Record statsd metrics for the invocation of arbitrary subprocesses (i.e.
**instrument**ation of arbitrary **bin**aries)

## Usage

```bash
binstrument -metric ci.task -tags env:prod,task:test -- make test
```

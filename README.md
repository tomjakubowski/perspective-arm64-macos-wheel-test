# perspective-oneoff-tests

- [actions](https://github.com/tomjakubowski/perspective-oneoff-tests/actions)

## local runs

doesn't really work but would go something like this. caveat executor

```
act -P ubuntu-22.04=catthehacker/ubuntu:act-22.04 -W .github/workflows/yourworkflow.yml --input foo=https://github.com/finos/perspective/actions/runs/11584577722
```

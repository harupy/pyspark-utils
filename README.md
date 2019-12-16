# pyspark-util

![test_status](https://github.com/harupy/pyspark-util/workflows/Test/badge.svg)

A set of pyspark utility functions.

```python
import pyspark_util as psu

...
```

## Development

### Setup

```
docker-compose build
docker-compose up -d
```

### Lint

```
docker exec psu-cnt ./tools/lint.sh
```

### Test

```
docker exec psu-cnt ./tools/test.sh
```

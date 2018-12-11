# 06-fox-tests

# NOTE: Please commit/push BEFORE running my tests. I'm not responsible if you fuck up because of my scripts

## How to acquire and run my test suite
```bash
# cd to 06-fox-<uname>
git clone https://github.com/armishra/06-fox-tests.git
cp 06-fox-tests/*.fox ./tests/input/
cp 06-fox-tests/*.json ./tests/

make clean && make
```

This basically acquires my tests files and overwrites yourTests.json with mine
and runs my test suite.

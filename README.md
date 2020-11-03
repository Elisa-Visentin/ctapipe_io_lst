# ctapipe_io_lst [![Build Status](https://travis-ci.org/cta-observatory/ctapipe_io_lst.svg?branch=master)](https://travis-ci.org/cta-observatory/ctapipe_io_lst)


EventSource Plugin for ctapipe, able to read LST zfits files
and calibration them to R1 as needed for ctapipe tools.


Create a new environment:
```
conda env create -n lstenv -f environment.yml
conda activate lstenv
pip install -e .
```

Or just install in an existing environment:
```
pip install -e .
```


## Test Data

To run the tests, a set of non-public files is needed.
If you are a member of LST, ask one of the project maintainers for the credentials
and then run

```
TEST_DATA_USER=<username> TEST_DATA_PASSWORD=<password> ./download_test_data.sh
```

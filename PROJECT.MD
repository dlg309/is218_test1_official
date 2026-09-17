# IS 218 Test 1 Calculator Project

## Student

Diego Guevara

## Purpose

This project is a small Python calculator package that implements addition and subtraction. It includes pytest tests to verify that both operations return the expected results.

## Setup

Create and activate a virtual environment:

```bash
python3.13 -m venv .venv
source .venv/bin/activate
```

Install the required dependencies:

```bash
python -m pip install -r requirements.txt
```

## Run Tests

Run the student tests:

```bash
python -m pytest
```

Run the student tests and supplied acceptance checks:

```bash
python -m pytest tests checks -v
```

## Assertion Explanation

An assertion compares the actual result returned by a function with the expected result. For example, a test can verify that adding `2` and `3` returns `5`. If the result is different, pytest reports the assertion as a failed test.

## Virtual Environment

The `.venv` directory is ignored because it contains machine-specific installed packages and can be recreated locally. The `requirements.txt` file is committed so another developer can install the same required dependencies.

## Issues

* Issue 1: [Set up a reproducible Python project](https://github.com/dlg309/is218_test1_official/issues/1)
* Issue 2: [Implement and test addition](https://github.com/dlg309/is218_test1_official/issues/2)
* Issue 3: [Implement and test subtraction](https://github.com/dlg309/is218_test1_official/issues/3)
* Issue 4: [Document and verify delivery](https://github.com/dlg309/is218_test1_official/issues/4)


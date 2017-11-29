[![PyPI version](https://badge.fury.io/py/PyUpdater-S3-Plugin.svg)](http://badge.fury.io/py/PyUpdater-S3-Plugin)

# PyUpdater S3 plugin

PyUpdater upload plugin for AWS S3

## Installing

    $ pip install PyUpdater-S3-plugin


## Configuration

System environmental variables

Optional - If set will be used globally. Will be overwritten when you add scp settings during pyupdater init

| Variable      | Meaning        |
| ------------- |-------------|
| PYIU_AWS_ID   | Your amazon api id |
| PYIU_AWS_SECRET      | You amazon api secret   |
| PYIU_AWS_BUCKET | Bucket name (optional)|

For windows users, this means you may have to set your environment variables through command prompt.
Linux users, use Export commands instead

Example:
SET PYU_AWS_ID=abcdefg
SET PYU_AWS_SECRET=abcdefg
pyupdater settings --plugin s3
ddwda


## Changes

* v1.1

    - Updated

        Compat with PyUpdater 0.19+

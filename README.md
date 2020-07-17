# hbase-thrift-python3
Fix some syntax compatible problems in hbase-thrift 0.20.4 for python3 environment.

First install thrift and hbase-thrift by pip tools.

```
pip install thrift hbase-thrift
```

Then copy HBase.py and ttypes.py to $pythonenv/dist-packages/hbase/ directory and overwrite these two files.

```
sudo cp HBase.py ttypes.py $pythonenv/dist-packages/hbase
```

If a virtualenv is configured, set the $pythonenv as the virtualenv path.

# Parquet Vendored Files

The files in this directory are generated by the thrift compiler from
[parquet.thrift](https://github.com/apache/arrow/blob/master/cpp/src/parquet/parquet.thrift)
We vendor these files so we don't need to bring in the entire thrift compiler
as a dependency.

These files are copied from [Tensorflow I/O](https://github.com/tensorflow/io/tree/227379d2d260667f2b74a3d5052c2b9044312d4a/third_party/parquet).
junit_tests(
  dependencies=[
    '3rdparty/jvm/com/google/guava:guava',
    '3rdparty/jvm/io/netty',
    '3rdparty/jvm/junit',
    '3rdparty/jvm/org/apache/thrift:libthrift-0.5.0',
    '3rdparty/jvm/org/mockito:mockito-all',
    '3rdparty/jvm/org/scalatest',
    'finagle/finagle-core/src/main/scala:scala',
    'finagle/finagle-thrift',
    'finagle/finagle-thrift/src/main/java:java',
    'finagle/finagle-thrift/src/test/java',
    'finagle/finagle-thrift/src/test/thrift:thrift-java',
    'finagle/finagle-thrift/src/test/thrift:thrift-scala',
    'scrooge/scrooge-core/src/main/scala:scala',
    'util/util-app/src/main/scala:scala',
    'util/util-core/src/main/scala:scala',
    'util/util-stats/src/main/scala:scala',
  ],
  resources=[
    'finagle/finagle-thrift/src/test/resources',
  ],
  sources=rglobs('*.scala'),
  fatal_warnings=True,
)

## Unreleased
  - Removed `jar-dependencies` dependency [#7](https://github.com/logstash-plugins/logstash-output-gemfire/pull/7)

## 2.0.7
  - Docs: Set the default_codec doc attribute.

## 2.0.6
  - Fix some documentation issues

# 2.0.4
  - Depend on logstash-core-plugin-api instead of logstash-core, removing the need to mass update plugins on major releases of logstash
# 2.0.3
  - New dependency requirements for logstash-core for the 5.0 release
## 2.0.0
 - Plugins were updated to follow the new shutdown semantic, this mainly allows Logstash to instruct input plugins to terminate gracefully, 
   instead of using Thread.raise on the plugins' threads. Ref: https://github.com/elastic/logstash/pull/3895
 - Dependency on logstash-core update to 2.0


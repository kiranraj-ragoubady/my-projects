# My Projects
A collection or portfolio of my personal projects.

## Elasticsearch Log Appender
An asynchronous Elasticsearch log appender for Spring Boot 3 applications. Supports automatic cleanup and inbuilt UX to browse through and highlight the logs from any thread or class.

### Features:
- Minimal effort & realtime log export to elasticsearch. The index name is configurable.
- Includes spanId and traceId data automatically if available.
- Support to store other selective MDC map data. You can mention which keys you need to export.
- Automatic cleanup of older logs. The horizon and cleanup trigger rate are configurable.
- An intuitive logs UX webpage is available at `\logs` (path is configurable) to search, highlight and browse through the logs.

![Image seems to be unavailable.](https://github.com/kiranraj-ragoubady/my-projects/blob/main/images/elasticsearch-log-appender-ux.png?raw=true)
_Created with Freemarker and Javascript_
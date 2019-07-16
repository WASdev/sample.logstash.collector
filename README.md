# sample.logstash.collector
  
This project contains the sample dashboards and configuration files to help you exploit the *logstashCollector-1.0* and *logstashCollector-1.1* features in Liberty.

### Subdirectories

Each logstashCollector version contains subdirectories for specific versions of WebSphere Liberty. Dashboards for a *lower* version of Liberty may be used for higher versions of Liberty.

> For example:
The files under *[logstashCollector-1.0/Kibana4/8.5.5.9+](logstashCollector-1.0/Kibana4/8.5.5.9+/20160216/)* may be used in *logstashCollector-1.0* for any version of Liberty 8.5.5.9 and above.

Dashboards are generally **not** backwards compatible and may lead to unexpected problems. This would mean that higher Liberty versions of dashboards are not compatible with lower Liberty versions of dashboards.

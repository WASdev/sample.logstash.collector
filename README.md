# sample.logstash.collector
  
This project contains the following samples for exploiting the *logstashCollector-1.0* and *logstashCollector-1.1* feature in Liberty:
* Logstash configuration file *(liberty_logstash.conf)*
* Index template *(liberty_logstash_template.json)*
* Kibana dashboard *(liberty-kibana4.json)*

### Subdirectories

Each logstashCollector version contains subdirectories for specific versions of WebSphere Liberty. Dashboards for a *lower* version of Liberty may be used for higher versions of Liberty.

> For example:
The files under *[logstashCollector-1.0/Kibana4/8.5.5.9+](logstashCollector-1.0/Kibana4/8.5.5.9+/20160216/)* may be used in *logstashCollector-1.0* for any version of Liberty 8.5.5.9 and above.

Dashboards are generally **not** backwards compatible and may lead to unexpected problems. This would mean that higher Liberty versions of dashboards are not compatible with lower Liberty versions of dashboards.

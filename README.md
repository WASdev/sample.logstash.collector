# sample.logstash.collector

This project contains the following samples for exploiting the *logstashCollector-1.0* and *logstashCollector-1.1* feature in Liberty: 
* Logstash configuration file *(liberty_logstash.conf)*
* Index template *(liberty_logstash_template.json)*
* Kibana dashboard *(liberty-kibana4.json)*

### Subdirectories
The sample files used for *logstashCollector-1.0* can be found in *version-1.0* directory and the files used for *logstashCollector-1.1* can be found in *version-1.1* directory.


Each logstashCollector version contains subdirectories for specific versions of WebSphere Liberty. Dashboards for a *lower* version of Liberty may be used for higher versions of Liberty.

> For example:
The files under *[version-1.0/16.0.0.1+](version1.0/16.0.0.1+)* may be used in *logstashCollector-1.0* for any version of Liberty 16.0.0.1 and above.

Dashboards are generally **not** backwards compatible and may lead to unexpected problems. This would mean that higher Liberty versions of dashboards are not compatible with lower Liberty versions of dashboards.

There is also a Beta directory under each *version-1.0* or *version-1.1* directory for use with Beta versions of Liberty. These dashboards are not guaranteed to be compatible with non-beta versions of Liberty.
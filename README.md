# sample.logstash.collector

This project contains the following samples for exploiting the *logstashCollector-1.0* and *logstashCollector-1.1* feature in Liberty: 
* Logstash configuration file *(liberty_logstash.conf)*
* Index template *(liberty_logstash_template.json)*
* Kibana dashboard *(liberty-kibana4.json)*

### Subdirectories
**Note: There are currently sample files under the main directory and the version-1.0 directory. These are for Liberty v8.5.5.9+ and are kept around to preserve external links (temporarily). If you require more updated dashboards, you must navigate to the appropriate Liberty version.**

The sample files used for *logstashCollector-1.0* can be found in *version-1.0* directory and the files used for *logstashCollector-1.1* can be found in *version-1.1* directory.


Each logstashCollector version contains subdirectories for specific versions of WebSphere Liberty. Dashboards for a *lower* version of Liberty may be used for higher versions of Liberty.

> For example:
The files under *[version-1.0/8.5.5.9+](version-1.0/8.5.5.9+)* may be used in *logstashCollector-1.0* for any version of Liberty 8.5.5.9 and above.

Dashboards are generally **not** backwards compatible and may lead to unexpected problems. This would mean that higher Liberty versions of dashboards are not compatible with lower Liberty versions of dashboards.

There is also a Beta directory under each *[version-1.0](version-1.0/Beta)* or *[version-1.1](version-1.1/Beta)* directory for use with the latest Beta versions of Liberty. These dashboards are not guaranteed to be compatible with non-beta and outdated beta versions of Liberty.
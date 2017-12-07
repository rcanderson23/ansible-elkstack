Role Name
=========

Installs an ELK stack on a CentOS 7 machine

Requirements
------------

CentOS 7

Role Variables
--------------

logstash_port: Port logstash should listen on  
logstash_ssl_cert: Location of ssl cert  
logstash_ssl_key: Location of ssl private key  
kibana_port: Port kibana should listen on  
kibana_ip: IP kibana should bind to  
kibana_elastic_url: URL kibana should use to connect to elasticsearch  
kibana_log_dest: location kibana logs should be written to  
elastic_ip: IP elasticsearch should bind to  
elastic_port: Port elasticsearch should listen on  

Dependencies
------------

None

Example Playbook
----------------

    - hosts: elk 
      roles:
         - elkstack

License
-------

GPLv2


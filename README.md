# mysql-logstash-pipeline
Logstash pipeline for parsing MySQL/MariaDB logs

[![CI](https://github.com/widhalmt/mysql-logstash-pipeline/workflows/Logstash%20Syntax/badge.svg?event=push)](https://github.com/widhalmt/mysql-logstash-pipeline/actions?query=workflow%3A%22Logstash+Syntax%22)

This pipeline is to be used with Logstash. You can set the type of the log as a field (e.g. `[mysql][logtype]: slowquery`)

This pipeline has fixed keys for input and output. Make sure your Logstash configuration puts the logs in the correct keys and fetches them. There's an Ansible role coming up that will allow for easy automatic connection.

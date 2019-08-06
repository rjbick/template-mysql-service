# template-mysql-service
Personally I am not a fan of installing extra crap when you don't have to. So I built this template using the outdated percona template as a guide. 
It has most of the items that the old percona template has but with no script. It works by grabbing all of the stats at one time converting them to json (yes I didn't use jq because I didn't want to install extra packages). 

## Installation
1. Import template.
2. Grab the user paramaters out of the template and add them to a file ie (/etc/zabbix/zabbix_agent.d/mysql.conf) on the zabbix agent.
3. Restart zabbix agent.

I am always open to suggestions so feel free to comment.

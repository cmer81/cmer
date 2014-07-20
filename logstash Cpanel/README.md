Configuration Logstash for cpanel and CSF
====

For [CSF] redirect your log iptables in file /var/log/frewall.log.
> Edit your /etc/rsyslog.conf and add 

```sh
kern.*                                                          /var/log/frewall.log
```

> after edit execute

```sh
/etc/init.d/rsyslog restart
```

[csf]:http://configserver.com/cp/csf.html

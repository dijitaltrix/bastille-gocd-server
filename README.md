## GoCD Server
Bastille Template: gocd-server

This is a BastilleBSD 'template' container. Similar to Docker containers it allows running lightweight 'VMs' on FreeBSD.

Fetch and apply this template with:

```shell
bastille bootstrap https://github.com/dijitaltrix/gocd-server
bastille template TARGET dijitaltrix/gocd-server
```

## Description
A 'GoCD Server' assigns tasks a 'GoCD Agent'.

By default this template will install the 'GoCD Server' under '/usr/local/gocd' and run as the 'gocd' user.

You can download a template for your 'GoCD Agents' here: 
https://github.com/dijitaltrix/gocd-agent

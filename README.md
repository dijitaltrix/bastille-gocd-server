## GoCD Server
Bastille Template: gocd-server

This is a 'template' for a BastilleBSD container.
Similar to Docker containers it allows running lightweight 'VMs' on FreeBSD.

Fetch and apply this template with:

```shell
bastille bootstrap https://github.com/dijitaltrix/gocd-server
bastille template TARGET dijitaltrix/gocd-server
```

## Description
A 'GoCD Server' assigns tasks a 'GoCD Agent'.

By default this template will install the go-server under '/usr/local/gocd' and run as the 'gocd' user.

You can download a template for your GoCD agents here: 
https://github.com/dijitaltrix/gocd-agent


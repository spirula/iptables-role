iptables
=========

Configure iptables for Linux systems

Role Variables
--------------
**ip_forward:** Enables or disables ip forwarding default value: 1

**incoming:** Dictionary variable that defines the ports and names for each service, these ports will be allowed for incoming requests, the default value:

```
incoming:
  - name: SSH
    port: 22
  - name: HTTP
    port: 80
  - name: HTTPS
    port: 443
```

**outgoing:** Dictionary variable that defines the ports and names for each service, these ports will be allowed for outgoing requests, the default value:

```
outgoing:
  - name: SSH
    port: 22
  - name: HTTP
    port: 80
  - name: HTTPS
    port: 443
  - name: SMTP1
    port: 25
  - name: SMTP2
    port: 587
  - name: SMTP3
    port: 465

```

License
-------

MIT

Author Information
------------------

This role was created by the operations team in spirula systems company

company website: http://www.spirulasystems.com/

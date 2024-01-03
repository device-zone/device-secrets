# device-secrets
Provides the secrets appliance.

This appliance does the following:

- Provides a mechanism by which other appliances can request the generation of secrets before they start.
- No user servicable parts at this time.

## before

- Deploy the device-secrets package.

```
[root@server ~]# dnf install device-secrets
```

This will usually happen as a prerequisite of the installation of other appliances.


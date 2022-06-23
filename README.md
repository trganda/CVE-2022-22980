# CVE-2022-22980

A local based poc of CVE-2022-22980, for the detail of this vulnerability see https://tanzu.vmware.com/security/cve-2022-22980.

> You need to install [mongodb](https://www.mongodb.com/try/download) on locahost before running.
> 
> And I've create a web based poc with docker on [dockerv](https://github.com/trganda/dockerv/tree/master/vuln/spring/spring-data-mongodb/CVE-2022-22980)

Run

```bash
mvn spring-boot:run
```

or open with IDEA, and launch the `AccessingDataMongodbApplication`

![](screenshot.jpg)


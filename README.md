adaptTo() 2015 - CONGA
======================

Code samples for talk about [CONGA](http://devops.wcm.io/conga/) at adaptTo() 2015 in Berlin:<br/>
[CONGA - Configuration generation for Sling and AEM](http://adapt.to/content/adaptto/2015/en/schedule/conga---configuration-generation-for-sling-and-aem.html)


Requirements
------------

* Java 8
* Maven 3.3


Try it out
----------

This CONGA example is based on a wcm.io sample project containing an AEM application and CONGA example roles and templates:<br/>
https://github.com/wcm-io/wcm-io-samples

Before generating the configuration you have to clone [this repo](https://github.com/wcm-io/wcm-io-samples.git) and execute `mvn clean install`.

Alternatively you can add the Sonatype OSS snapshot repo to your maven settings; the snapshots of the sample project are published there:<br/>
https://oss.sonatype.org/content/repositories/snapshots/

To build the configuration clone the [current repository](https://github.com/adaptto-conf/2015-conga.git) and execute:
```
mvn clean package
```

You will find the generated confgiuration at `target/configuration`.

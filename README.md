# Apache httpclient Fluent API with liberal SSL certs policy

Slightly modified [Apache HTTPClient API](https://hc.apache.org/httpcomponents-client-ga/tutorial/html/fluent.html)

Changes

* no SSL certs checks
* no hostname checks

Use for dev purposes only in order to avoid java keystore certs config hells.

## How to build

```
mvn install
```

## How to use

```
<dependency>
          <groupId>org.apache.httpcomponents</groupId>
          <artifactId>fluent-hc-nossl-checks</artifactId>
          <version>4.4.1</version>
<\dependency>          
```          

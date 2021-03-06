<!--
   ====================================================================
   Licensed to the Apache Software Foundation (ASF) under one
   or more contributor license agreements.  See the NOTICE file
   distributed with this work for additional information
   regarding copyright ownership.  The ASF licenses this file
   to you under the Apache License, Version 2.0 (the
   "License"); you may not use this file except in compliance
   with the License.  You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing,
   software distributed under the License is distributed on an
   "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
   KIND, either express or implied.  See the License for the
   specific language governing permissions and limitations
   under the License.
   ====================================================================

   This software consists of voluntary contributions made by many
   individuals on behalf of the Apache Software Foundation.  For more
   information on the Apache Software Foundation, please see
   <http://www.apache.org />.
 -->
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
</dependency>          
```          

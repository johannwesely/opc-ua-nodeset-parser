UANodeSet Parser
================

A parser for the OPC UA UANodeSet XML schema.

Changes:
+Changed javax imports to jakarta imports
+Changed SerializationContext to EncodingContext so the parser works togehter with milo/dev1.0 Branch.
+Updated UaNodeset.xsd to newer Version.
+pom.xml changed to Snapshot 0.5.1 and to work with milo/dev1.0

### From Maven
```xml
<dependency>
    <groupId>com.digitalpetri.opcua</groupId>
    <artifactId>uanodeset-parser</artifactId>
    <version>0.5.1-SNAPSHOT</version>
</dependency>
```

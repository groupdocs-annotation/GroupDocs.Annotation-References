---
title: ConsoleLogger
second_title: GroupDocs.Annotation for Java API Reference
description: Represents logger implementation which sends all messages to console.
type: docs
weight: 10
url: /java/com.groupdocs.annotation.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.annotation.logging.ILogger](../../com.groupdocs.annotation.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Represents logger implementation which sends all messages to console.
## Constructors

| Constructor | Description |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Methods

| Method | Description |
| --- | --- |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Logs error message. |
| [warning(String message)](#warning-java.lang.String-) | Logs warning message. |
| [trace(String message)](#trace-java.lang.String-) | Logs the process of annotating. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Logs error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |
| exception | java.lang.Exception | The exception that was thrown. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Logs warning message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Logs the process of annotating.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |


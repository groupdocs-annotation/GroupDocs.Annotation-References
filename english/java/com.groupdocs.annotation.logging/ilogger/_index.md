---
title: ILogger
second_title: GroupDocs.Annotation for Java API Reference
description: Logger.
type: docs
weight: 11
url: /java/com.groupdocs.annotation.logging/ilogger/
---```
public interface ILogger
```

Logger.
## Methods

| Method | Description |
| --- | --- |
| [error(String message, Exception ex)](#error-java.lang.String-java.lang.Exception-) | Error message. |
| [warning(String message)](#warning-java.lang.String-) | Warning message. |
| [trace(String message)](#trace-java.lang.String-) | Trace message. |
### error(String message, Exception ex) {#error-java.lang.String-java.lang.Exception-}
```
public abstract void error(String message, Exception ex)
```


Error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The string to log. |
| ex | java.lang.Exception | The exception that was thrown. |

### warning(String message) {#warning-java.lang.String-}
```
public abstract void warning(String message)
```


Warning message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The string to log. |

### trace(String message) {#trace-java.lang.String-}
```
public abstract void trace(String message)
```


Trace message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The string to log. |


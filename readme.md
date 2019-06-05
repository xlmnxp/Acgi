# Acgi
Support module for Common Gateway Interface (CGI) scripts.

# How to Import
```
import "Srl/String.alusus"
import "Apm.alusus"
Apm.importFile("xlmnxp/Acgi");
Acgi.initHeader();

Srl.Console.print("<h1> Server Name: %s </h1>", Acgi.getServerName());
```

# Methods
- Acgi.**initHeader()**: Bool<br>
creater header with content type `text/html`.
- Acgi.**getQueryString()**: ptr[Word[8]]
- Acgi.**getRequestMethod()**: ptr[Word[8]]
- Acgi.**getContentType()**: ptr[Word[8]]
- Acgi.**getContentLength()**: ptr[Word[8]]
- Acgi.**getScriptName()**: ptr[Word[8]]
- Acgi.**getRequestUri()**: ptr[Word[8]]
- Acgi.**getDocumentUri()**: ptr[Word[8]]
- Acgi.**getDocumentRoot()**: ptr[Word[8]]
- Acgi.**getServerProtocol()**: ptr[Word[8]]
- Acgi.**getRequestScheme()**: ptr[Word[8]]
- Acgi.**getHttps()**: ptr[Word[8]]
- Acgi.**getGatewayInterface()**: ptr[Word[8]]
- Acgi.**getRemoteAddr()**: ptr[Word[8]]
- Acgi.**getRemotePort()**: ptr[Word[8]]
- Acgi.**getServerAddr()**: ptr[Word[8]]
- Acgi.**getServerPort()**: ptr[Word[8]]
- Acgi.**getServerName()**: ptr[Word[8]]
- Acgi.**getRedirectStatus()**: ptr[Word[8]]
# LICENCE
MIT Licence.
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
- Acgi.**getQueryString()**: array[Char]
- Acgi.**getRequestMethod()**: array[Char]
- Acgi.**getContentType()**: array[Char]
- Acgi.**getContentLength()**: array[Char]
- Acgi.**getScriptName()**: array[Char]
- Acgi.**getRequestUri()**: array[Char]
- Acgi.**getDocumentUri()**: array[Char]
- Acgi.**getDocumentRoot()**: array[Char]
- Acgi.**getServerProtocol()**: array[Char]
- Acgi.**getRequestScheme()**: array[Char]
- Acgi.**getHttps()**: array[Char]
- Acgi.**getGatewayInterface()**: array[Char]
- Acgi.**getRemoteAddr()**: array[Char]
- Acgi.**getRemotePort()**: array[Char]
- Acgi.**getServerAddr()**: array[Char]
- Acgi.**getServerPort()**: array[Char]
- Acgi.**getServerName()**: array[Char]
- Acgi.**getRedirectStatus()**: array[Char]
# LICENCE
MIT Licence.
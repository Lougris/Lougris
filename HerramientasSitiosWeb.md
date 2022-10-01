Información sobre herramientas de escaneo de vulnerabilidades para sitios web.

1.- BurpSuite https://portswigger.net/burp
¿Qué es Burp Suite?

Burp Suite es una plataforma digital que reúne herramientas especializadas para realizar pruebas de penetración en aplicaciones web. 
Burp Suite cuenta con dos versiones: una versión gratuita (Burp Free) y una versión de pago (Burp Professional).
Las diferenciaremos para establecer cómo se usan en el hacking ético de páginas web.

Burp Suite Community Edition

Burp Suite Community Edition es la versión gratuita de esta plataforma, viene instalada por defecto en el sistema operativo Kali Linux, ParrotOS, etc.
y su función principal es la de actuar como proxy HTTP de la aplicación para realizar pentesting.

Un proxy HTTP es una herramienta que se usa en el hacking ético de páginas web con el fin de interceptar el tráfico de red, 
lo cual permite analizar, modificar, aceptar o rechazar todas las solicitudes y respuestas de la aplicación.

Burp Suite Pofessional

Burp Proffessional es un software de pago desarrollado por la empresa PortSwigger. Incluye, además del proxy HTTP, algunas herramientas de 
pentesting web como:

    Escáner de diferentes tipos de vulnerabilidades web.
    Módulo Spider de detección de contenido indexado.
    Programas para hacer fuzzing.
    Funciones colaborativas.
    
    
   
2.- Owasp Zap    https://owasp.org/www-project-zap/
¿Qué es Owasp Zap?

Zed Attack Proxy (ZAP) es una herramienta gratuita de prueba de penetración de código abierto que se mantiene bajo el paraguas del 
Open Web Application Security Project (OWASP). ZAP está diseñado específicamente para probar aplicaciones web y es flexible y extensible.

ZAP es lo que se conoce como un “proxy de intermediario”. Se encuentra entre el navegador del probador y la aplicación web para que pueda 
interceptar e inspeccionar los mensajes enviados entre el navegador y la aplicación web, modificar el contenido si es necesario y luego 
reenviar esos paquetes al destino. Se puede utilizar como una aplicación independiente y como un proceso demonio.

ZAP tiene versiones para cada sistema operativo principal y Docker, por lo que no está atado a un solo sistema operativo. 
Debido a que ZAP es de código abierto, el código fuente se puede examinar para ver exactamente cómo se implementa la funcionalidad.

Puede encontrar un botón de donación en la página owasp.org para ZAP en https://owasp.org/www-project-zap/ .


INSTALAR ZAP

Lo primero que debe hacer es instalar ZAP en el sistema en el que desea realizar el pentesting. Descargue el instalador adecuado de la página 
de descargas .

Tenga en cuenta que ZAP requiere Java 8+ para funcionar. El instalador de Mac OS / X incluye una versión adecuada de Java, pero debe instalar
Java 8+ por separado para las versiones de Windows, Linux y multiplataforma. Las versiones de Docker no requieren que instales Java.

Una vez que se complete la instalación, inicie ZAP y lea los términos de la licencia. Haga clic en Aceptar si acepta los términos, y ZAP 
terminará de instalarse, luego ZAP se iniciará automáticamente.




3.- Vega Vulnerability Scanner  https://subgraph.com/products/index.en.html
¿QUÉ ES VEGA VULNERABILITY SCANNER?

Vega es una herramienta gráfica de auditoría web gratuita y de código abierto.

Esta herramienta realiza diversas funciones tales como:

     Análisis de Vulnerabilidades
     Crawler (copia del sitio web)
     Análisis de contenido
     Modificación manual de paquete HTTP (proxy)

La herramienta tiene módulos para realizar ataques típicos del OWASP como XSS, SQL Injection, 
Directorio transversal, URL Injection, detección de errores, etc.

INSTALACIÓN DE VEGA

Para instalar Vega solo tendremos que hacer click en el siguiente enlace, teniendo en cuenta nuestro sistema operativo.
También debemos descargar la última versión de JAVA.

     Descargar Vega:

https://subgraph.com/vega/download/index.en.html

     Descargar JAVA

https://www.java.com/es/












   

---
title: Seguridad Informatica
author:
  name: Tomas Palma
  link: https://blog.tomasps.tk/posts/Seguridad-Informatica
date: 2022-02-17 10:28:00 +0800
categories: [seguridad informatica]
tags: [seguridad, informatica]
comments: true
toc: true
render_with_liquid: true
image:
  src: /Internet-Safety.jpg
  width: 800
  height: 500
---


<iframe data-aa='1953952' src='//ad.a-ads.com/1953952?size=728x90' style='width:728px; height:90px; border:0px; padding:0; overflow:hidden; background-color: transparent;'></iframe>


# Que hacer si se pierde o te roban el móvil?

Si algún día te roban el movil o lo pierdes, tienes que hacer lo siguiente
## Android
1. Inicia sesión con tu cuenta de google en otro dispositivo movil, o desde un ordenador a traves de un navegador web.
2. Después de iniciar sesíon, dirigete hacia [Mi dispositivo](https://myaccount.google.com/find-your-phone) y selecciona tu telefono movil.


> Trata de bloquear el móvil cuanto antes, para que no se pueda acceder a la información.
{: .prompt-tip }

> Salvo que des el móvil por perdido no pulses bajo ningún concepto la opción **Borrar dispositivo**, dado que ésta borrará todos los datos del dispositivo y lo bloqueará.
{: .prompt-danger }
## iPhone
> No puedo proporcionar información 100% viable dado que no dispongo de un teléfono de apple.

1. Inicia sesion en [iCloud](https://www.icloud.com/)
2. Seleciona tu dispositivo

# Infección de virus en el ordenador.

Desde mi punto de vista, tampoco puedo decir mucho dado que nunca he sido infectado porque uso un nivel de seguridad demasiado alto al navegar por internet. No obstante yo recomiendo usar:
1. Una VPN[^1] al navegar por sitios no muy confiables dado que estos puede contener traqueadores para rastrear tu ubicacion.
2. Tratar de no descargarse archivos o programas pirata. Estos pueden ser modificados para tener un funcionamiento no adecuado, siempre antes de ejeacutar cualquier archivo no confiable analizarlo con el antivirus y en el caso de no disponer de uno analizarlo a través de esta web virustotal[^2].
3. Usar sistemas operativos licenciados oficialmente (Windows11/10, MacOS, Ubuntu y otros)

## Como actuar?

Si alguna vez, tienes la mala suerte de ser infectado por un virus, te recominedo hacer lo siguiente.
### Windows
1. Normalmente windows defender (el antivirus integrado de windows) deberia ser suficicente, pero Windows 7/10/11 tienen una herramienta para quitar el malware llamada **MRT**.
![Desktop View](/malware.png){: width="550" height="550" }
_Microsoft MRT_

<br>
### Android
1. Hay algunas aplicaciones en la PlayStore[^3] que funcionan como antivirus, una de ellas es la de Kaspersky

# Phishing. ¿Qué es?
> Phishing es el delito de engañar a las personas para que compartan información confidencial como contraseñas y números de tarjetas de crédito.

Uno de los mejores ejemplos es lo que está pasando ahora mismo en discord.
Este Phishing trata de engañar al usuario haciendole creer que ha sido premiado con 3 meses gratis de discord premium, pero cuando te metes al enlace, te pide la contraseña y el nombre de usuario, lo cual es un poco sospechoso.
Una vez introducido el nombre y la contraseña, un bot se encarga de comprobar esas credenciales en la página de discord para ver si son correctas, si es asi, el bot se encarga de difundir el mismo enlace por todos los canales e amigos que ese usuario tenia.

Se pueden identificar varios tipos de phishing

## Spear phishing
Este tipo de phishing ataca a una persona u organizacion especifica, a menudo con contenido personalizado para la victima o victimas. Requiere de un reconocimiento previo al ataque para descubrir nombres, cargos, direcciones de correo electronico y similares.

> Spear phishing es una amenaza crítica para empresas (y gobiernos), y cuesta mucho dinero. Según un informe de 2016 de una investigación sobre el tema, el spear phishing fue responsable del 38% de los ciberataques en las empresas participantes durante 2015.

## Phishing de clonación
En este ataque, los delincuentes hacen una copia, o clonan, correos electrónicos legítimos enviados anteriormente que contienen un enlace o un archivo adjunto. Luego, el autor del phishing sustituye los enlaces o archivos adjuntos con contenido malicioso disfrazado para hacerse pasar por el auténtico.

## Phishing telefónico
Con los intentos de phishing a través del teléfono, a veces llamados phishing de voz o “vishing,” el phisher llama afirmando representar a su banco local, la policía o incluso la Agencia Tributaria.

### Phishing telefonico (sms)
Phishing vía SMS, o “smishing,” es el gemelo malvado del vishing, que realiza el mismo tipo de estafa (algunas veces con un enlace malicioso incorporado en el que hacer clic) por medio de un mensaje de texto SMS.

## Como identificar un ataque de phishing.
1. Normalmente el atacante se hace pasar por alguna empresa y/o particular bien sea mediante teléfono o correo.
2. Google Chrome, puede detectar (no al 100%) algunos phishing activando su *Protección mejorada* en los ajustes.

![Desktop View](/phishing.jpg){: width="550" height="550" }
_Ejemplo de Phishing haciendose pasar por PayPal_

# Malware
> La palabra malware viene del inglés, y y es el resultado de la unión de las palabras malicious software o software malicioso.
Se trata de un tipo de software o de aplicacion que tiene como objetivo hacer daño al dispositivo.

Se pueden distinguir varios tipos de *malware*

## Amenaza por contagio
Este tipo de amenazas hace referencia a un tipo de malware cuya característica principal es que se pueden replicar y distribuir a través de las redes de comunicación a otros ordenadores. A este tipo amenaza pertenece los **virus** y los **gusanos**:

### Virus
Es una forma de malware toma el control del equipo infectado sin autorización y causa daños sin que el usuario se de cuenta. Los virus son un tipo de programa que se auto-incluyen en otros ficheros, como por ejemplo programas ejecutables, y, gracias a su capacidad de autorreplicación, extienden la infección de un ordenador a otro. Entre los daños que pueden causar, se puede destacar la denegación de servicios y la degradación del rendimiento

### Gusanos
Los gusanos son un tipo de software malicioso que puede funcionar de forma independiente y no se añaden a otros programas para propagarse. Suelen explotar alguna vulnerabilidad de seguridad mediante el uso de ordenadores o recursos de red y se propagan a través de dispositivos de almacenamiento como dispositivos USB o del correo electrónico. Pueden causar problemas de rendimiento de la red y consumir gran cantidad de memoria de los recursos del sistema


> El tipo de malware más común son los virus. Existe una gran cantidad de tipos de virus y dependiendo de la fuente a la que acudamos podemos encontrar tipos distintos. A continuación, vamos a citar los tipos encontrados en dos de estas clasificaciones

## Amenaza enmascarada
A este tipo de amenaza pertenecen los malware que se introducen en el ordenador a través de
aplicaciones u otros tipos de ficheros que parecen inofensivos. A este grupo de pertenecen los
trojanos y Rootkits:

### Troyanos
Es una porción de software maligno que se oculta y se comporta como un programa legítimo para tomar el control no autorizado de un ordenador. El troyano no se autoreplica, en su lugar se descarga a través de la interacción del usuario, como la descarga de un archivo de Internet. Puede robar contraseñas o datos de inicio de sesión, dinero de cuentas bancarias, modificar/eliminar archivos y supervisar la actividad del usuario.

### Rootkit (encubridor)
Los rootkits son las técnicas de enmascaramiento de malware diseñados para ocultar el malware de los programas de eliminación de virus. Se puede instalar a través de un “exploit” de software o un trojano. Generalmente, su objetivo es robar contraseña e Instalar “Keyloggers”, programas que registran las pulsaciones de teclado y permitir al hacker un acceso de administrador al ordenador infectado.


En muchos de los casos los virus utilizan troyanos para infectar un ordenador. Un virus puede ser instalado a través de un programa inocuo a través de un juego o una aplicación. También se han encontrado troyanos en forma de script como adjunto a un correo electrónico que puede descargar un virus desde una página web.


## Amenaza de registro de actividad
En este grupo podemos encontrar todo el malware que tiene como objetivo registrar la actividad
que realizar el usuario. Los malwares más destacados de este grupo son: Spyware y keylogger.

### Spyware
Es un software que afecta negativamente a un sistema al realizar un seguimiento de la actividad del usuario sin su consentimiento y enviar la información confidencial a su creador. Se puede instalar a través de algún programa,como por ejemplo “freeware” o través de troyanos. Existen “spyware” muy sofisticados que capturan toda la información que pasa por la interfaz de red, robando de esta forma certificados digitales, claves u otro tipo información confidencial.

### Keylogger
Es un tipo de “spyware” que, si que el usuario lo detecte, graba todas las pulsaciones de teclas. Con esta información y la proporcionada por las“cookies” y los archivos del ordenador, puede capturar todo tipo de datos personales. Puede ser instalado por otro programa malicioso o al visitar un sitio infectado. Entre la información más peligrosa que pueden robar está el nombre de usuario y contraseña, número de tarjetas de crédito o datos bancarios.



> Hay que tener en cuenta que los spyware pueden ser utilizados legalmente. Algunas empresas los utilizan para vigilar cómo sus empleados usan las tecnologías que las compañías les ofrecen. También puede ser usado por los padres para vigilar la actividad de sus hijos en Internet.




# Banners
Los típicos botones de descarga, reproducción de vídeo, los que te avisan de que eres el ganador de un sorteo o aquellos que te informan que tu sistema está infectado con un virus, son claros ejemplos de banners que solo buscan la difusión de diversos virus.

# Contactos en redes sociales
Más de 28 millones. Este es el dato de usuarios de redes sociales en España. Facebook y Youtube encabezan el ranking de redes con más perfiles en nuestro país, según el estudio de Hootsuite. WhatsApp, les sigue de cerca y cada vez son más los internautas que se decantan por Instagram como red social para compartir sus fotografías y vídeo

Sea cual sea la red social preferida, lo cierto es que no son pocos los usuarios de redes sociales que desconocen los riesgos de seguridad que puede generar el uso de estas herramientas.

Para tratar de evitar los principales problemas que se generan en Internet, a continuación te compartimos unos consejos para proteger tus redes sociales, principalmente para los más jóvenes.


## No aceptes como amigo a desconocidos
Este consejo es importante seguirlo en redes sociales donde se comparte contenido más personal, por ejemplo, Instagram o Facebook.

Aceptar como contacto todas aquellas peticiones que te llegan a tus redes sociales puede desembocar en un problema de seguridad, pues no sabes quién está detrás de esos perfiles que pueden usar tus imágenes con fines poco deseados.

## Puedes poner tus cuentas como "privadas"
De esta manera, solo tus contactos, a los que tú has aceptado, podrán ver tus publicaciones en redes sociales. Cada una de ellas tiene opciones de privacidad, desde abiertas a todos sus usuarios hasta privadas, en las que únicamente pueden ver tus contenidos quienes tú elijas y, si te buscan, únicamente podrán ver la información que tú decidas.


## Comprueba lo que publicas
Este consejo es especialmente importante si te encuentras de viaje, no ofrezcas información de dónde te encuentras, por cuántos días y cuándo sales de viaje. Estás ofreciendo una información que compromete tu seguridad. Más si tienes tus redes sociales abiertas a todos los usuarios.

## Utiliza contraseñas robustas en tus redes sociales
Y no solo eso, también diferentes. Así, si consiguen descubrir tu contraseña de una red social no podrán acceder al resto. Utiliza una  contraseña con, al menos, mayúsculas, minúsculas y números. Evita usar las típicas: “1234” o tu fecha de cumpleaños.

En esta [pagina web](https://www.security.org/how-secure-is-my-password/) puedes comprobar la seguridad de tu contraseña


# Enlaces


















[^1]: [VPN](https://en.wikipedia.org/wiki/Virtual_private_network)
[^2]: [Virustotal](https://www.virustotal.com/gui/home/url)
[^3]: La tienda de aplicaciones propia de Google implementada en los androids

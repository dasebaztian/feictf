# getip

<figure><img src="../../.gitbook/assets/imagen (11).png" alt=""><figcaption><p>When your web request is forwarded through web servers, there is a header that is being added that notifies the next server, who is this request forwarded for... In order to solve this you will have to make your IP appear as either localhost or 127.0.0.1.</p></figcaption></figure>

Al entrar al sitio del reto podemos ver un sitio que nos muestra que nuestra IP no esta permitida, recordando un poco de la descripción del reto podemos notar que se hace referencia a un encabezado de HTTP que permite decirle al siguiente servidor quien ha reenviado esta petición, también nos dice que debemos usar localhost o 127.0.0.1.

Haciendo una busqueda en internet podemos encontrar cómo haciendo uso de la herramienta burpsuite podemos agregar este encabezado a nuestra petición.

{% embed url="https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Forwarded" %}

<figure><img src="../../.gitbook/assets/imagen (12).png" alt=""><figcaption><p>flag del reto getip</p></figcaption></figure>

Al agregar este header a nuestra petición HTTP podemos obtener nuestra flag

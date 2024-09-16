# hostel

<figure><img src="../../.gitbook/assets/imagen (6).png" alt=""><figcaption><p>There is a hidden site on this system, but you'll have to guess the proper Host header.</p></figcaption></figure>

Para este reto se nos menciona mucho el termino de Host, y al entrar al sitio nos dice que si podemos encontrar el ETSCTF host.

Por lo que haciendo uso de una herramienta de proxy web, cómo lo es Burpsuite nos pondremos a escuchar el tráfico para poder manipular los paquetes.

<figure><img src="../../.gitbook/assets/imagen (8).png" alt=""><figcaption></figcaption></figure>

Una  vez que estemos escuchando al hacer la petición de GET podemos ver los encabezados de la petición, enviaremos la petición al repeater para hacer mas fácil el proceso.

Desde el repeater podemos ver la petición que estamos haciendo junto a la respuesta que nos da el sitio web

<figure><img src="../../.gitbook/assets/imagen (9).png" alt=""><figcaption></figcaption></figure>

Recordando un poco podemos notar que el encabezado Host esta presente, encabezado que se menciona mucho desde el nombre de reto y su descripción, podemos probar distintos Host cambiando el valor que por defecto sera la IP o dominio del servidor por otro que nosotros queramos y dar al botón "Send" para ver la respuesta que nos da. Probando y analizando nos daremos cuenta que la respuesta sigue siendo la misma, "Can you find the hidden **ETSCTF** host?",  entonces probaremos ese Host

<figure><img src="../../.gitbook/assets/imagen (10).png" alt=""><figcaption><p>flag del reto hostel</p></figcaption></figure>

Al probar con este nombre de host el servidor nos responderá con una página diferente que ya contiene nuestra flag.
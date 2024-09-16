
<figure><img src="../../.gitbook/assets/imagen (2).png" alt=""><figcaption><p>JaSON and the Argonauts invite you to join them in the search of the missing endpoints</p></figcaption></figure>

Para este reto se nos presenta un servidor de JSON, con algunos endpoints de API que han sido perdidos. Al entrar podemos ver que se nos da una pista de cómo es que funciona el json-server a través de un enlace al repositorio oficial de GItHub.

<figure><img src="../../.gitbook/assets/imagen (3).png" alt=""><figcaption></figcaption></figure>

Al hacer una pequeña búsqueda sobre el repositorio podemos ver que se describen los pasos que se tienen que seguir para empezar a utilizar el servidor, al analizar estos pasos podemos ver que el servidor se inicia haciendo referencia a un archivo **db.json** o **db.json5** que contiene todos los endpoints del servidor, lo que nos hace pensar que podría ser el mismo archivo sobre el cual también se ha iniciado este reto.

<figure><img src="../../.gitbook/assets/imagen (5).png" alt=""><figcaption><p>Flags del reto argonauts</p></figcaption></figure>

Al consultar el endpoint podremos ver las 3 flags que incluye el reto. **Este reto también se puede resolver por fuerza bruta, usando un fuzzer. Intentarlo de esta forma para ganar experiencia con este tipo de herramientas. **_**Recomendamos: gobuster**_
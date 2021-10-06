## Asegurando Tus Fondos

Como se mencionó en el capítulo anterior, nuestro objetivo es alcanzar el nivel "Tus llaves, tus monedas".

Para comprar, usar y almacenar bitcoins, vas a necesitar:

* Una Cartera de Bitcoin = Tu caja de depósitos de dinero digital. Una analogía más precisa es un llavero digital de llaves para tus “alcancías digitales”.
* Direcciones de Bitcoin = Una o más direcciones únicas para tus fondos en la cadena de bloques o bien tus ordenes de pago (más precisamente “salidas de transacción sin gastar”, o de sus siglas en inglés, “UTXO”)
* Una Semilla = los datos de recuperación de tu cartera de Bitcoin.

### Cartera de Bitcoin
Piensa en una cartera como una caja de seguridad pública con múltiples secciones. Cualquiera puede depositar dinero en cada una de las secciones. Solo el propietario de las llaves privadas puede desbloquear una sección y mover el dinero que tiene. Tu cartera Bitcoin consta de todas las secciones y contiene todas las llaves privadas para desbloquearlas. Las llaves privadas y las direcciones de Bitcoin se generan a partir de la semilla. La semilla es la raíz de todas las llaves y direcciones, es como un depósito en el que se almacenan todas tus llaves privadas.

![Definición de términos](assets/__seed-postbox.png) [^69]

La cartera es una aplicación en tu teléfono o software en tu computadora, que maneja todo en segundo plano: tus llaves privadas, tus direcciones y el envío y recepción de bitcoins.

Las carteras de Bitcoin contienen llaves, no monedas. Cada usuario posee una cartera que contiene llaves. Las carteras son en realidad solo llaveros que contienen pares de llaves privadas y públicas. Tus fondos se registran es en la cadena de bloques de Bitcoin.

### Dirección de Bitcoin
Para recibir bitcoins, necesitas una dirección de bitcoins a la que alguien pueda enviarte bitcoins. Una dirección de Bitcoin consta de una larga serie de dígitos y letras.

Un ejemplo de una dirección de Bitcoin: 346n4apJCQPg2XAXU3bfNQTogz4PyTkrEf

Por supuesto, escribir 34 dígitos es muy poco práctico, por lo tanto, los códigos QR de las direcciones se usan comúnmente y generalmente se crean automáticamente en tu cartera.

![Dirección BTC como código QR](assets/_address-book.PNG)

Bitcoin es seudónimo, lo que significa que no es necesario que conectes tu dirección de correo electrónico o identificación personal con una cartera. Sin embargo, la cadena de bloques de Bitcoin es transparente, lo que significa que tus direcciones de Bitcoin se pueden ver públicamente en Internet. Por ejemplo, puedes buscarla en Blockcypher y ver todas las transacciones y valores actuales. Aquí hay un enlace de ejemplo: [https://anita.link/explorer](https://anita.link/explorer)

Por lo tanto, por razones de privacidad, no compartas tus direcciones de Bitcoin si van a quedar vinculadas a tu identidad en Internet. La privacidad es también la razón por la que no debes reutilizar las direcciones. La mayoría de las carteras de Bitcoin te proporcionan automáticamente direcciones nuevas para cada transacción.

Vayamos a la parte más importante para asegurar tus bitcoins: la semilla.

### Semillas y Llaves Privadas

Dado que la semilla es la raíz de todas las llaves privadas, nadie más debe tener acceso a ella. La persona que conozca la semilla tendrá el control final sobre los fondos.

La semilla (a veces llamada frase mnemónica o frase de respaldo) es una secuencia de 12 o 24 palabras en inglés que te da acceso a las llaves privadas de las direcciones de tu cartera y, por lo tanto, acceso a tus monedas. Esto significa que este orden de palabras debe permanecer secreto. Cualquiera que conozca la semilla puede acceder y hacerse cargo de tus monedas. ¿Por qué?

Tus monedas no están dentro de tu cartera digital, como podrían estarlo dentro de tu cartera física habitual. En cambio, estas se registran en la cadena de bloques. Compara esto con un correo electrónico y una carta. Puedes acceder a tu cuenta de correo electrónico desde cualquier lugar del mundo porque tus correos electrónicos se almacenan en línea, mientras que tu buzón está estacionario en un lugar fijo. Esto se aplica de manera similar a Bitcoin.

El acceso mundial a tus activos siempre será posible con la semilla, independientemente del fabricante de tu cartera. Al seleccionar tu cartera, busca el término "HD wallet" (Cartera “HD”, del inglés “jerárquico-determinista”). Las carteras HD te permiten cambiar a la cartera HD de otro fabricante, tomar la semilla y restaurar tus monedas.

Supón que tu teléfono inteligente se corrompe, y ya no puedes acceder a tu aplicación de cartera Bitcoin y necesitas cambiar a un teléfono nuevo. Instala una versión nueva de tu cartera Bitcoin e importa la semilla de tu primera cartera. Así restableces el acceso a tus fondos.

La aplicación de cartera genera la semilla durante la configuración inicial. La mayoría de las carteras te guiarán a través de la configuración y le indicarán que escribas las palabras iniciales en una hoja de papel. Si tu cartera no te ofrece eso de inmediato, busca la función "Crear copia de seguridad" o "Copia de seguridad" y sigue los pasos. La creación de la semilla funciona de manera opuesta a la creación de una contraseña como la conocemos comúnmente en los sitios web. No eres tú quien determina la contraseña, sino la propia cartera.

¡El orden de las palabras es IMPORTANTE! Debes escribir las palabras exactamente en el orden en que aparecen.

> Ejemplo de semilla: “cruise item paper slim vocal power like video snap museum mirror sun”

Haz una copia de tu semilla a mano en una hoja de papel y guárdala de forma segura. No tomes una captura de pantalla, no la guardes en tu teléfono o computadora que esté conectada a Internet, ya que todos esos lugares pueden ser pirateados. Hay más información sobre seguridad en el capítulo 5.

Dado que tus fondos no están dentro de tu cartera, sino almacenados en la cadena de bloques, puedes moverte globalmente y llevar tus fondos de bitcoin a donde quiera que vayas. Solo necesitas recordar las 12-24 palabras iniciales en el orden correcto. Después de pasar la aduana sin un teléfono móvil, obtienes una nueva billetera e importas la semilla. Magia.

[^69]: Anita Posch, inspirada por Andreas M. Antonopoulos

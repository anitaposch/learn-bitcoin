# Usando Bitcoin

## Comisiones de Red
Se debe pagar una comisión de minería o comisión de red por cada transacción de bitcoin y estas comisiones son necesarias para que continúe el funcionamiento de la red de Bitcoin. El trabajo de los mineros se ve recompensado con estas comisiones y con el bitcoin recién acuñado (consúltese el capítulo 2.3). La minería es un factor esencial en el protocolo Bitcoin. Una vez que se ha minado un bloque nuevo de transacciones, se adjunta a la cadena de bloques. Esta es la forma de garantizar la seguridad de la red. Dado que Bitcoin tiene un límite de suministro fijo de 21 millones de monedas, los mineros ya no recibirían ninguna remuneración por su desempeño después de alcanzar este suministro máximo, y ya no estarían interesados en procesar transacciones y así mantener la cadena de bloques. Por lo tanto, Satoshi Nakamoto introdujo las comisiones de red. Según el documento técnico (donde se denominan “transaction fees”), el objetivo es mantener estas comisiones más bajas que las comisiones y costos comparables del sistema bancario tradicional. Sin embargo, no se da el caso de que las transferencias sean gratuitas simplemente porque, en teoría, no exista la necesidad de intermediarios o bancos.

Cuando compramos bitcoins a través de una casa de cambios, las comisiones de red (las comisiones por minería) generalmente no las podemos ajustar nosotros y la fija el proveedor.

En nuestra cartera Bitcoin sin custodia, sí podemos determinar por nosotros mismos las comisiones de red para los pagos efectuados. Cuanto más alta establezcamos esta comisión, más rápido será procesada nuestra transacción por los mineros porque ellos eligen primero las transacciones con las comisiones más altas. Si nuestra transferencia no es urgente, podremos elegir una comisión más baja.

Para tener más control, podemos estimar las comisiones y la velocidad de confirmación en páginas como [Mempool.space](https://mempool.space/) o [Johoe's Bitcoin Mempool](https://jochen-hoenicke.de/queue/). Estos sitios web muestran el número y el tamaño de todas las transacciones por confirmar. Ofrecen una vista en tiempo real y muestran cómo evoluciona el tanque de memoria de Bitcoin. Las transacciones están coloreadas por la cantidad de comisión que pagan por byte (o “byte virtual”).

![Vista en tiempo real de transacciones por confirmar](assets/_Mempool-space-white-back.png) [^74]

A continuación, podemos ver la configuración de comisiones en la cartera Edge. Podemos elegir uno de los rangos de comisiones de red predeterminados o un valor personalizado.

![Configuración de las comisiones de red en la cartera Edge](assets/_transaction-fee-setting.png) [^75]

**Transacción Pendiente**
Dado que los bloques nuevos se minan cada 10 minutos, tomará un promedio de al menos 10 minutos hasta que se confirme nuestra transacción. Si establecemos una comisión de red demasiado baja, entonces nuestra transacción podría permanecer sin confirmar por un período más largo a medida que el Mempool (o tanque de memoria) se libere y los mineros comiencen a volver a incluir transacciones con tarifas más bajas. Aquí se puede ver una de mis transacciones que ha estado atrapada en el Mempool ¡durante un mes!
![Transacción pendiente](assets/_Pending-transaction-edge.png) [^76]
Puedes buscar el estado de tu transacción en un [Explorador de Bitcoin](https://blockchair.com). Como puede verse a continuación, mi transacción está a 4.717 rangos de ser minada con un total de 41.610 transacciones en el Mempool. Elegí una tarifa de 5 sat por vbyte.
![Estado de la transacción como se muestra en blockexplorer](assets/_Pending-transaction-explorer.png) [^77]

No es necesario que sigas los pasos a continuación para lograr que tu transacción original sea incluida en un bloque. La mayoría de las transacciones con tarifas bajas siguen siendo válidas durante días y finalmente se confirmarán. Sin embargo, hay dos formas de resolver el problema de una transacción estancada y lograr que se confirme antes.

**Cuando Una Transacción Enviada Se Estanca**
* Podemos aplicar un “Replace by Fee” (RBF) o “Reemplazo por Comisión”: algunas carteras nos permiten establecer esta opción en sí antes de enviar una transacción. En este caso, si la transacción original se estanca, podemos establecer una tarifa más alta y reenviar la misma transacción.

**Una Pago Entrante Está Estancado**
* Podemos aplicar el método “El Hijo Paga Por el Padre” (de sus siglas en inglés “CPFP” o “Child Pays For Parent”): podemos pensar en esto como un padre que no tiene dinero suficiente para sus gastos, por lo que su hijo paga la diferencia en nombre del padre. CPFP es una técnica a través de la cual podemos acelerar nuestras transacciones entrantes lentas por confirmar, al realizar una nueva transacción con tarifas más altas (una transacción secundaria) utilizando las salidas (las UTXOs o los fondos) de la transacción anterior (transacción principal) que está bloqueada.

Consúltese la documentación de la cartera que se está utilizando para obtener instrucciones detalladas.

## Comprar Algo con Bitcoin
Aquí hay algunos directorios con tiendas donde podemos gastar bitcoins.
* [Aceptado aquí](https://www.acceptedhere.io)  
* [Servicios B2B que aceptan BTC](https://cryptwerk.com/companies/b2b/btc/)  
* [Coinmap](https://coinmap.org/view/); tiendas físicas que aceptan Bitcoin  
* Directorio [Spending Bitcoin](https://spending-bitcoin.com/)  
* Directorio [UseBitcoins](https://usebitcoins.info/)  

## Tarjetas de débito Bitcoin
Podemos usar una tarjeta de débito Bitcoin para comprar cualquier cosa como si fuese cualquier otra tarjeta de débito bancaria. La diferencia es que la misma está cargado con bitcoins o altcoins. La compañía de débito paga a los comerciantes en su propia moneda y el cargo se deducirá de nuestro saldo en bitcoins, lo que nos permite vivir exclusivamente a través de bitcoin.

Deberá depositar sus bitcoins en la compañía de la tarjetas de débito, lo que significa que debemos ceder el control de esas monedas a un tercero. Así que más vale depositar solo lo que necesitemos en la tarjeta y verificar las tarifas que cobran esas compañías de tarjetas.

Una breve lista de tarjetas que están disponibles en este momento:  
Cryptocom Visa, Binance, Bitpanda Visa, Coinbase Visa, Wirex Visa, BlockCard, Cryptopay, Nexo, Bitwala Visa, BitPay Visa y Cash App.

## Gastar y recibir
Las siguientes son herramientas y servicios que nos permitirán gastar y recibir BTC en nuestra vida diaria.
* [Bity](https://bity.com/products/crypto-online-bill-pay/); paga facturas en línea con bitcoin
* [Cash App](https://cash.app/bitcoin); compra y vende BTC directamente desde el saldo de tu aplicación Cash
* [Strike](https://global.strike.me/); envía y recibe pagos internacionales instantáneos, remesas instantáneas y con acceso completo a la red Bitcoin
* [Piixpay](https://www.piixpay.com/?lang=en); paga a cualquiera en EURO usando tu cripto
* [Bitrefill](https://www.bitrefill.com/?hl=en); compra tarjetas de regalo y recargas de teléfonos

[^74]: [Captura de pantalla de Anita Posch] (https://mempool.space)  
[^75]: captura de pantalla de Anita Posch, billetera Edge  
[^76]: captura de pantalla de Anita Posch, billetera Edge  
[^77]: Captura de pantalla de Anita Posch, Blockchair  

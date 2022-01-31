¿Qué es DigiByte? 
----------------

DigiByte (DGB) es una cadena de bloques global descentralizada de tres años de rápido crecimiento que se centra en la seguridad cibernética, los pagos y las tecnologías de comunicaciones seguras.

Para obtener más información, así como una versión binaria de uso inmediato de
el software DigiByte Core, consulte  https://digibyte.io

DigiByte FAQ
-------------
Fecha de lanzamiento: 10 de enero de 2014

Tipo de cadena de bloques: pública, descentralizada, basada en UTXO, multialgoritmo

Símbolo de cotización: DGB

Genesis Block Hash: "USA Today: 10 de enero de 2014, objetivo: datos robados de hasta 110 millones de clientes"

Suministro total máximo: 21 mil millones de dígitos en 21 años (2035)

Oferta Actual: 8.107.031.908 DGB (Mayo 2017)

Inflación de la Oferta Anual: 12% en 2017

Reducción de recompensas en bloque: 1% mensual

Recompensa de bloque actual 891 DGB

Algoritmos de minería: cinco (Sha256, Scrypt, Groestl, Skein y Qubit)

Tiempo de bloque: bloques de 15 segundos (1,5 minutos por algoritmo)

Cuota de bloque de Algo: 20 % de cuota de bloque por Algo (5)

Retarget de dificultad cada 1 bloque, 5 dificultades separadas, 1 para cada algoritmo de minería

Compatibilidad con SegWit Sí. Primera altcoin importante en activar con éxito Segwit. (abril de 2017)

Bifurcaciones 4. DigiShield, MultiAlgo, MultiShield, DigiSpeed

Bifurcaciones blandas 3. SegWit, CSV, NVersionBips

Puede minar DigiByte en uno de los cinco algoritmos de minería separados. Cada algoritmo extrae un promedio del 20 % de los bloques nuevos. Esto permite una descentralización mucho mayor que otras cadenas de bloques. Para que un atacante pueda forzar DigiByte, el atacante necesitaría controlar el 93% del hashrate en 1 algoritmo y el 51% de los otros 4, lo que hace que DigiByte sea mucho más seguro contra ataques PoW que otras cadenas de bloques.

DigiShield Hardfork: Bloque 67,200, 28 de febrero de 2014

MultiAlgo Hardfork: bloque 145k, 1 de septiembre de 2014

MultiShield Hardfork: bloque 400k, 10 de diciembre de 2014

Hardfork de DigiSpeed: Bloque 1,430,000 4 de diciembre de 2015 

DigiByte vs Bitcoin
-------------------

Seguridad: 5 algoritmos de minería de DigiByte frente a 1 algoritmo de Bitcoin.
La minería de DigiByte está mucho más descentralizada.
Los algoritmos de minería de DigiByte se pueden cambiar en el futuro para evitar la centralización.

Velocidad: las transacciones de DigiByte ocurren mucho más rápido que las transacciones de Bitcoin.
Notificaciones de transacciones de 1 a 3 segundos.
Bloques DigiByte de 15 segundos frente a bloques Bitcoin de 10 minutos.
Los DigiBytes se confirman después de 1,5 minutos frente a 1 hora con Bitcoin.

Volumen de transacciones: DigiByte puede manejar muchas más transacciones por segundo.
Bitcoin solo puede manejar 3-4 transacciones por segundo.
DigiByte actualmente puede manejar más de 280 transacciones por segundo.
La bifurcación dura DigiSpeed ​​de 2015 introdujo cambios que duplican la capacidad de la red cada dos años.

Suministro total: más DigiBytes, precio más bajo, más micro transacciones, mejor estabilidad de precios.
Se crearán 21 mil millones de DigiBytes en 21 años.
Solo se crearán 21 millones de Bitcoins durante 140 años.
relación 1:1000. 1 Bitcoin por cada 1000 DigiBytes.

Flexibilidad: Capacidad para agregar rápidamente nuevas características.
DigiByte puede agregar nuevas funciones y actualizaciones mucho más rápido que Bitcoin.
Las futuras actualizaciones de DigiByte impulsarán el límite de transacciones a varios miles por segundo.

Comercialización y usabilidad: DigiByte es una marca fácil de comercializar entre los consumidores.
DigiBytes son mucho más baratos de adquirir.
$1 - $10 precio objetivo a largo plazo por DigiByte.
Envía 5 DigiBytes en lugar de 0,005 Bitcoin.


Licencia
-------

DigiByte Core se publica bajo los términos de la licencia MIT. Ver [COPYING](COPYING) para más
información o ver  https://opensource.org/licenses/MIT.

Proceso de desarrollo
-------------------

La rama `master` se construye y prueba regularmente, pero no se garantiza que sea
completamente estable. [Tags](https://github.com/digibyte/digibyte/tags) son creados
regularmente para indicar nuevas versiones de lanzamiento oficiales y estables de DigiByte Core.

El flujo de trabajo de contribución se describe en [CONTRIBUTING.md](CONTRIBUTING.md).


Pruebas
-------

Las pruebas y la revisión del código son el cuello de botella para el desarrollo; obtenemos más tirón
solicitudes que podemos revisar y probar a corto plazo. Por favor sea paciente y ayude haciendo pruebas
solicitudes de extracción de otras personas, y recuerde que este es un proyecto crítico para la seguridad en el que cualquier error podría costarle a la gente
mucho dinero.

### Pruebas automatizadas

Se recomienda encarecidamente a los desarrolladores que escriban [unit tests](src/test/README.md) para el nuevo código, y para
envíe nuevas pruebas unitarias para el código anterior. Las pruebas unitarias se pueden compilar y ejecutar
(suponiendo que no estuvieran deshabilitados en la configuración) con:`make check`. Más detalles sobre la ejecución
y ampliar las pruebas unitarias se pueden encontrar en [/src/test/README.md](/src/test/README.md).

también hay[pruebas de regresión e integración](/qa) de la interfaz RPC, escrito
en Python, que se ejecutan automáticamente en el servidor de compilación.
Estas pruebas se pueden ejecutar (si las [dependencias de prueba](/qa) están instaladas) con: `qa/pull-tester/rpc-tests.py`

El sistema Travis CI se asegura de que cada solicitud de extracción se cree para Windows, Linux y OS X, y que las pruebas de unidad/sanidad se ejecuten automáticamente.

### Pruebas manuales de control de calidad (QA)

Los cambios deben ser probados por alguien que no sea el desarrollador que escribió el
código. Esto es especialmente importante para cambios grandes o de alto riesgo. Es útil
para agregar un plan de prueba a la descripción de la solicitud de extracción si probar los cambios no
es sencillo.


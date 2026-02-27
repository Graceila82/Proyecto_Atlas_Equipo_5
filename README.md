# 📚 PROYECTO GRUPAL ATLAS – EQUIPO 5

# 🔎 Observaciones Generales

Realizamos una valoración inicial del dataset proporcionado y partimos de la conclusion de trabajar sobre un fichero incompleto y poco fiable para realizar un efectivo análisis de datos que pueda proporcionar a la dirección de la biblioteca mejoras efectivas. Por lo que las conclusiones que vamos a ofrecer se basan unicamente, en el análisis de la información proporcionada.

Los datos proporconados nos indican fechas, categorías, meses, horarios, plazos de entrega, idioma.

---

## 📝 1. Hallazgos iniciales:

* **Desorden cronológico:** Existen registros de fecha que no siguen una secuencia lógica.
* **Inconsistencia de registros:** El dataset cuenta con **261 registros**, lo que indica que hay más de 100 días al año sin actividad registrada.
* **Limitación de variables:** La ausencia de identificadores de usuario o títulos específicos limita la profundidad de las conclusiones.
* **Falta de contexto operativo:** Se desconoce el reglamento oficial de la biblioteca (plazos de devolución y renovaciones).

---

## 📊  2. Análisis Detallado:


### ➡ Registros:

El dataset registra **un único préstamo por día**. Hay 261 registros en total, por lo que este dato nos proporciona las siguientes conclusiones:

* 104 días sin registro, ¿Cuál es el motivo de la falta de dato? ¿Días de no apertura? ¿Días de apertura pero sin préstamos? ¿festivos?
* ¿Por que hay solo un registro por día? no se entregan, devuelven, renuevan más libros ese día?

Con los datos aportados, nos falta información imprescindible para comenzar con una valoración efectiva.


### ➡ Categorías:


Calculamos el % que respresenta cada categoría y observamos que:
* **Ficción (39%):**, es la categoría mas prestada. 
* **Poesía (1%):**, es la categoría menos prestada. 

<img width="600" height="371" alt="PRESTAMOS POR CATEGORIA" src="https://github.com/user-attachments/assets/8235f2eb-1a66-4b57-b324-8d256a40b7e6" />


Observando estos datos nos preguntamos:

* ¿Cuántos libros hay de cada categoría en la biblioteca?
* El % de préstamo que obtenemos pordíra indicarnos que Ficción es el caballo ganardor de la biblioteca, pero si lo commparamos con la reprención total de libros de ficción, este dato seguiría siendo positivo? ¿Y poesía? ¿seguiría siendo el patito feo?


### ➡ Idioma:

Observamos que se registran 3 idiomas. Castellano, Inglés y Catalán.

* **Castellano (80%):** Idioma predominante en todas las categorías. En conclusión podemos decir que la biblioteca contiene libros mayoritariamente en Castellano.
* **Catalán (11%):** Segundo idioma más representativo. La biblioteca está en Cataluña. Este idioma no se oferta en todas las categorías.
* **Inglés (9%):** Solo registrado para dos categorías, principalmente ficicón. Podemos entender que este idioma no se oferta en todas las categorías.


<img width="600" height="371" alt="IDIOMAS Y CATEGORIAS" src="https://github.com/user-attachments/assets/93fbafa1-dc2d-4b4e-9a20-5c9307b95df6" />



Teniendo en cuenta el registro 0 de prestamos en catalán e inglés, ¿existen libros de esas categorías en la biblioteca? Si no hay ¿interesaría probar a introducirlo en las categorías mas prestadas en castellano como Comic?


### ➡ Calendario-Horarios:


Intetamos encontrar un patrón lógico de dias de apertura, que nos desvele el horario de la biblioteca, pero no es muy concluyente.
No hay un patrón fijo, ni por trimestres, ni por semestres. Los unicos patrones encontrados son:

<img width="600" height="371" alt="MESES POR DÍAS" src="https://github.com/user-attachments/assets/116faadb-1337-42cc-8f0d-0af693a05e8d" />

* La biblioteca abre todos los Martes y Domingos a lo largo del año.
* De Enero a Mayo abre todos los días de la semana.
* Julio y Agosto abren los Martes, Jueves, y Domingo.
* El resto de meses abre Martes, Miércoles, Viernes y Domingos.

En los datos podemos observar que al abrir siempre los Martes y Jueves, el % de prestamos de esos días es el más elevado, seguido de los Miércoles y Viernes, por ultimo y con menos entregas los Jueves, Lunes y Sabado.

No tenemos un patrón de horarios de apertura, por lo tanto, ¿cuántos Martes y Viernes al año se han abierto? ¿cuantos Miercoles y Viernes al año se han abierto? la información que nos aporta nuestro grafico puede variar si tenemos en cuenta el número total de días de apertura.

Hay un cambio de horario a partir de verano. ¿En verano tiene un horario especial?¿porque a partir de verano los horarios de apertura son menores con respecto a Enero-Mayo? comparandolo con el patrón estacional, coinciden que los prestamos de invierno y primavera (Enero-Mayo) son superiores al resto de meses, provablemente por mayor días de apertura. Por lo tanto podemos sacar en conclusión que menos días de apertura, hay menos préstamos.

<img width="600" height="371" alt="PATRÓN ESTACIONAL" src="https://github.com/user-attachments/assets/068b24cd-48e7-48e3-bd92-419234d49321" />


### ➡ Horarios:

<img width="600" height="371" alt="FRANJA HORARIA POR MESES" src="https://github.com/user-attachments/assets/0e730a9b-cbab-41de-8f71-771aa475034a" />


Tendencia clara hacia la **tarde** en todos los meses. Lo que nos puede indicar que el usuario principal es joven o familiar.

---

## 🧐 3.¿Qué nos ha llamado la atención?

El principal dato llamativo es que solo tengamos un registro por día. Desvirtua los datos y no se puede hacer una análisis óptimo. Las conclusiones realizadas **no es reales.**, no son efectivas para la toma de decisiones que se quieran realizar para una mejora de servicio y optimización de recursos.
No hay identificativos de usuario que nos aporten datos de renovación.
Los datos de horarios de apertura no siguen un patrón. Pero hemos podido observar que reducir el horario no ha optimizado el servicio.
No hay datos de stock por categorías e idiomas que nos puedan aportar mas contexto y hacer una valoración mas precisa.

---

## ❓ 4. Preguntas.

* ¿Existen préstamos digitales?
* ¿Cuál es el periodo máximo de préstamo permitido? ¿Varía en función de la categoría?
* ¿Nos aportaría información si es un registro de renovación? en tal caso ¿sería apropiado analizarlo y aumentar los días de préstamo?
* ¿Los días sin registro son cierres por festivos o falta de demanda?

---


## 📖 **Recursos**

https://docs.google.com/spreadsheets/d/1mfcCf_hN9Hm_4hM69Fcu6w0PcZ9IwsRWL5iJugFbwQw/edit?usp=sharing
https://docs.google.com/spreadsheets/d/1gV-55rOgNQYgT7u4lgXKWIWf1prytUqzY3xrk8pNmSI/edit?usp=sharing

# Proyecto_Atlas_Equipo_5
Repositorio Proyecto Grupal Atlas, Equipo 5

# TAREA 5
## DIAGRAMAR CON UML

Ahora que tienes una mejor comprensión sobre la diagramación, es momento de analizar
algunos casos. En cada uno de ellos, tendrás que identificar los atributos, las
responsabilidades y el constructor más adecuado según el contexto. Después, crearás los
diagramas de clases usando DrawIO.

###Ejercicio N° 1

Imagina que el tío Rico tiene una cuenta en el banco UAGro Bank. Cada vez que realiza un
retiro, verifica varios aspectos de su cuenta: que el nombre del titular sea el suyo, que el saldo
esté correcto y que el número de la cuenta también sea el adecuado. El tío acaba de empezar
a usar la página web de su banco, que le permite retirar, depositar y recibir transferencias a
través de su número de cuenta. Para acceder a su cuenta, necesita que le muestren su saldo,
el titular de la cuenta, su número de cuenta y su alias.
Cuando abrió su cuenta de caja de ahorros, le pidieron su nombre y el saldo inicial. Con ese número que le asignaron, quedó registrada su cuenta.

**Actividad**

Modela la clase CajaDeAhorros para que sea utilizada en un sistema del banco. Agrega los
atributos y métodos que consideres necesarios para cubrir los requerimientos del ejercicio.
Recuerda pensar en un constructor adecuado para esta clase.

---

### Ejercicio N° 2

Daniel es cliente de UAGro Bank y tiene una cuenta corriente que le permite emitir cheques
para realizar pagos de electrodomésticos. El banco ofrece dos tipos de cheques:

- **Cheque común**
- **Cheque de pago diferido**

Cada cheque tiene una fecha de emisión y una fecha de vencimiento. Además, el cheque
puede ser transferido a otras personas mediante un endoso, lo cual significa que Daniel debe
escribir en el reverso del cheque los datos del nuevo propietario. Los cheques tienen un plazo
máximo de 30 días desde la fecha de vencimiento para ser presentados.

**Actividad**

Modela la clase **Cheque** para que pueda ser utilizada en un programa del banco. Incluye los
atributos, métodos y un constructor adecuado para que refleje las funcionalidades
mencionadas.

---

### Ejercicio N° 3

Un día cualquiera en la veterinaria, llega el joven pitbull llamado Dorian, acompañado de su
dueño César. El veterinario Julio lo está esperando en el consultorio 1 para atenderlo,
mientras que, en el consultorio 2, sale el gatito Lito Rodríguez, que tiene 4 años. Cada
veterinario tiene asignado un consultorio. Durante las consultas, las mascotas son pesadas,
medidas y se registra su estado de salud, que puede ser: **regular, bueno o muy bueno.**

Los clientes acostumbran pagar las consultas a fin de mes, por lo que se les acumula el
importe de las consultas, así como la cantidad de ellas.

**Actividad**

Identifica las clases que se mencionan en la narrativa y modela un diagrama de clases. Define
los atributos, métodos y constructores correspondientes a cada clase que debe intervenir en
este proceso.

---

### Ejercicio N° 4

La veterinaria siempre necesita tener cajas de provisiones para revender o para usarlas
durante las consultas de los animales. Estas cajas tienen varias características importantes,
como:

- **Peso total**
- **Origen**
- **Nombre del proveedor**
- **Descripción del contenido**
- **Si se debe manejar con cuidado, en caso de que el contenido sea frágil.**

**Actividad**

Identifica los atributos y métodos que debería tener la clase **CajaDeProvisiones**. Considera
agregar un constructor adecuado y modela esta clase utilizando UML. Asegúrate de que
refleje todas las necesidades mencionadas en el planteamiento.

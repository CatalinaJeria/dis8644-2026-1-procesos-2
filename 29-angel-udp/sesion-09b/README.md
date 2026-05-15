# sesion-09b

viernes 15-05-2026

## Apuntes

El chip Dip-16: número de patas

W7.62 mm: ancho de patas

Repaso en KiCad después de realizar la tarea

Y enseña a cómo realizar cambios en cuanto a las huellas mientras se va actualizando ida y vuelta reiteradamente

Y también se pueden editar los componentes en cuanto a nombres, colores o partes de esta, como agregar o quitar patitas en chip en caso de que se pueda

### Botones

Están los switch y los temporales

Temporary - Pulsadores - Pushbuttons - Timbres, tienen un sentido que es: Normalmente abierto NO y Normalmente cerrado NC

Una cosa es el Polo: físicamente hay una conexión

El Throw: en qué lugares puede caer

Y el Single: tiene un lugar donde caer

Y una Com (común) para decidir a dónde va y se llama single porque en la carcasa solo hay una

El que usamos es el pushbbutton que en el esqumatico tiene 2 patas porque están duplicadas (mecanicamente hay 4 pero electricamente hay 2 creo que esto eta para mejorar la estbilidad) Huella SW_PUSH_6mm

### Interruptores

Hay de 2 patas y tambien pushbbutton de 2 patas en el esquematico así que ninguno me dice si es switch o no

SPDT: SW_SPDT (lo vamos a usar generalmente para prender y apagar)

Tal como editamos los simbolos, podemos editar la huella manualmente

Hay componentes de placa y componentes de panel

---

**los de panel** son los que van en las carcasas

Se puede conecar por medio de palaras que evita un cableado directo sino que sería conceptual

Ala izquierda hay opciones para sacar la visualizacción de Tierra o GND

Todo EL GND deve estar completa y no generar "islas aisladas" que no tengan toda la conexión con ground porque puede no funcionar el circuito

Con la letra F se pasan los componentes para a tras y con la letra R se acomoda en el mismo punto en el que estaba

 En propiedades de las huellas se puede cambiar el modelo 3D para ajustar la posición

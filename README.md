# Notas para el examen de certificación CompTIA Security+ (SY0-601)

Notas personales de estudio para la certificación CompTIA Security+ (SY0-601)

## Dominios

La certificación se divide en 5 grandes dominios
- Ataques, amenazas y vulnerabilidades
- Aquitectura y diseño
- Imlementación
- Operaciones y respuesta a incidentes
- Gobernanza, riesgo y cumplimiento

## Generalidades de Seguridad

### Triada CID (CIA)

Los pilares de Seguridad de la Información son **C**onfidencialidad *(Confidenciality)*, **I**ntegridad *(Integrity)* y **D**isponibilidad *(Availability)*

#### Confidencialidad

Asegura que la información solo pueda ser conocida por personas autorizadas.

#### Integridad

Asegura que la información no cambie sin tener la correta autorización.

#### Disponibilidad

Asegura que la información estatá accesible en el momento que sea requerida.

### La triple A de la seguridad (AAA)

Se compone de los siguiente conceptos Autenticación *(Authentication)*, Autorización *(Authorization)* y Contabilidad *(Accounting)*

#### Autenticación *(Authentication)*

Ocurre cuando se determina la identidad de una persona a traves de una prueba y se confirma por el sistema, para garantizar que la persona que usa el sistema es quien dice ser. Los posibles retos de autenticación se dividen en categorías.

- Algo que usted sabe
    - Nombre de usuario y contraseña
    - Pin 
- Algo que usted es
    - Huella digitla
    - Escaneo del ojo
    - Escaneo de retina
    - Reconocimiento facial
- Algo que usted tiene
    - Un token
    - Un celular
    - Una cédula
    - Una tarjeta de cédito/debito
- Algo que usted hace
    - La forma en que usted habla
    - La forma en que usted escribe su firma
    - La forma en que usa los dispositivos
- Algún lugar donde usted está
    - Ubicación GPS

#### Autorización *(Authorization)*

La autorización ocurre cuando una persona tiene acceso a algúna información o área dentro de un sistema o edificio.

#### Contabilidad *(Accounting)*

Se refiere a llevar un seguimiento detallado de las acciones, datos y uso de red que suceden en un ambiente, mediante archivos de registo (Log files), porque si se tiene una violación de datos (Data breach) o alguna amenaza interna (Insider Threat) se puede verificar dentro de los archivos de registo e identificar quien y cuando realizó las acciones.

La generación de pruebas de las acciones realizadas se conoce como **No repudio**.

### Amenazas de seguridad

Existen 4 categorías principales de amenazas que se pueden encontrar en un ambiente corporativo.

#### 1) Malware

Es todo aquel software creado con objetivos maliciosos, como dañar equipos, robar información o manipular redes de comunicación.

#### 2) Acceso no autorizado

Sucede cuando se obtene acceso a un recurso informático o a información sin la debida autorización del propietario. Por ejempo si puede adivinar la contraseña de otra persona y usuarla para suplantar su identidad es una forma de acceso no autorizado.

#### 3) Fallos de sistema

Como su nombre lo indica se trata del momento en que los sistemas dejan de funcionar por un problema en su programación.

#### 4) Ingeniería social

Es la acción de manipular a las personas para revelar información confidencial o realizar otras acciones que puedan resultar perjudiciales para una empresa.

### Mitigación de amenazas

Existen 3 principales categorías para mitigar las amenazas

#### 1) Controles físicos

Son todos los conroles que se puedan utilizar para evitar que sucedan cosas en el entorno del mundo real.

- Candados
- Identificaciones
- Camaras de seguridad
- Guardas de seguridad
- Puertas
- Alarmas

#### 2) Controles técnicos

#### 3) Controles administrativos
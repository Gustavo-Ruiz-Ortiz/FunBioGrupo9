# Biodiseño Equipo 9

- Nicole Medina

- Gustavo Ruiz

- Nicolas Caballero

- Enrique Alcantara

- Valeria Rivera

## Análisis del caso:

PCR o reacción en cadena de la polimeras es una técnica usada para la replicación del ADN cada etapa de este proceso trata del aumento o disminución de temperaturas para un ciclo completo. Son tres etapas : 
1. Desnaturalización.En esta etapa, las cadenas de ADN son calentadas y separadas a una temperatura de 92º a 98º C durante 20-30 segundos, esto con el fin de romper los enlaces puentes de hidrógenos que existe entre las dos hebras de la cadena de ADN y asi poder separarlas.
2. Hibridación. En esta etapa los primers se alinean al extremo 3’, de esta forma necesitamos reducir la temperatura.
3. Extensión. Se permitirá sintetizar la nuevas cadenas de ADN, dependiendo del tipo de enzima polimerasa se elevará la temperatura hasta 72ºC.



**(Pruebas PCR y detección de infecciones con Termociclador)**

Gracias a este proceso de reproducción / replicación del ADN, se crearon las Pruebas de Diagnóstico de PCR. Esta técnica fundamental simple pero potente de biología molecular utiliza las enormes cantidades de copias de ADN sintetizadas a partir de un número reducido de moléculas de las mismas para detectar de forma rápida y precisa enfermedades infecciosas y alteraciones genéticas. Se identifica el material genético (ADN / ARN) de un patógeno o células anómalas en una muestra, lo que permite precisar los signos de una enfermedad en una fase temprana de la infección.

Dado a que la prueba PCR permite detectar todo tipo de anomalías genéticas en las muestras de los pacientes, se pueden detectar un gran número de enfermedades infecciosas o similares. Unos ejemplos son los siguientes:

* Virus
* Agente patógenos (Listeria, Legionella, Borrelia, Leptospira, Chlamydia)
* Cáncer
* Retrovirus (VIH, Hepatitis C)
* Parásitos (Toxoplasma, Trypanosoma, Cryptosporidium)

La prueba de PCR se desarrolla mediante el siguiente procedimiento:

Toma de una fuente de ADN (sangre, saliva o tejido)
Se añade la muestra en una màquina especial donde es añadida una enzima polimerasa para que se produzca la replicación
Luego de una hora y el ADN se replicara millones de veces, la máquina indicará una anomalía en el código genético

La máquina especial utilizada para las pruebas PCR, se denomina Termociclador, cuya función esencial para la replicación correcta del adn es mantener los ciclos de temperatura necesarios para llevar a cabo la reacción en cadena. 


## FORMULACIÓN DE LA PROBLEMÁTICA
***¿Cómo podríamos diseñar un termociclador microfluídico que sea portatil para estudio en campo enfocado en la educación?***


## Estado del Arte Científico

### Patentes de invención o utilidad

| Código     |Ventajas                           | Imagen                     |
|--------------|-----------------------------------|----------------------------|
|EP2703497A1|La presente descripción está dirigida a un chip microfluídico para la generación de gotitas acuosas para la amplificación de ácidos nucleicos, comprendiendo dicho chip microfluídico a) un primer depósito para la absorción de un líquido hidrófobo que termina en al menos una entrada o al menos una entrada proveniente de un exterior depósito de líquido hidrofóbico, cada entrada termina en un primer canal microfluídico que conecta al menos un primer depósito con un recipiente de reacción, b) al menos un elemento que comprende un segundo depósito para la absorción de una solución hidrofílica que termina en una entrada vertical en un segundo microfluídico canal que conecta el segundo depósito con un primer canal de microfluidos, c) al menos una unión en T entre dicho primer y segundo canal de microfluidos, caracterizado porque el extremo de dicho segundo canal de microfluidos está unido radial y horizontal al primer canal de microfluidos.|![](https://patentimages.storage.googleapis.com/28/13/91/162fde7379b99b/imgf0003.png)| 
|ES2891303T3|Incluye una tarjeta microfluídica integrada, la tarjeta microfluídica integrada comprende: un ensamble de placa con canales; una pluralidad de módulos modulares en conexión microfluídica entre sí y cada uno configurado y dispuesto para detectar ácido nucleico, la pluralidad de módulos modulares incluye: un módulo de reactivos configurado y dispuesto para contener y suministrar reactivos a otro de la pluralidad de módulos modulares; un módulo de lisis configurado y dispuesto para llevar a cabo la lisis en una entrada de muestra a la tarjeta microfluídica integrada; un módulo de purificación configurado y dispuesto para purificar objetivos en la muestra de otro material en la muestra; un módulo de reacción en cadena de la polimerasa (PCR) configurado y dispuesto para amplificar y marcar los objetivos; y un módulo de detección configurado y dispuesto para hibridar los objetivos amplificados y marcados para la detección de los objetivos amplificados y marcados; una cámara de entrada configurada y dispuesta para recibir la muestra e introducir la muestra en los canales.|![]()|
|ES2617599T3|Sistema diseñado para el diagnostico de variedades de muestras en paralelo |![]()|

## Estado del Arte Comerciales

### Productos Comerciales

| Nombre     |Características                           | Imagen                     | Precio                  |
|--------------|-----------------------------------|----------------------------|------------------------------|
| TERMOCICLADOR EN TIEMPO REAL miniPCR® mini16|Termociclador portatil que cuenta con una app donde se puede visualizar el proceso de replicación del adn|![](https://www.minipcr.com/wp-content/uploads/DSC_0234-1-450x450.png)|
|PCR DIGITAL (dPCR) Naica®System|La muestra fluye a través de una red de microcanales y luego se divide en una gran variedad de gotitas individuales organizadas formando un cristal.|![](https://bonsailab.com/wp-content/uploads/2021/07/naica-system-updated-1200x675-1-600x338.jpg)| 
|Termociclador microfluídico ChipGenie® edition T| El instrumento ChipGenie® edition TSO permite controlar la temperatura de los chips microfluídicos en formato de portaobjetos. Se puede realizar tanto una temperatura fija como ciclos de temperatura para permitir, por ejemplo, una PCR rápida en el chip. El ChipGenie® edition TSO está equipado con una unidad de lectura basada en la fluorescencia para llevar a cabo la detección óptica en los chips microfluídicos de la plataforma ChipShop siguiendo el espacio de una placa de 384 pocillos de 4,5 mm con posiciones fijas de lectura.|![](https://img.medicalexpo.es/images_me/photo-mg/111519-15498230.webp)|

Requiere ordenador adicional.

### Termocicladores OpenHardware
| Nombre     |Características                           | Imagen                     |
|--------------|-----------------------------------|----------------------------|
| OpenPCR|Es un termociclador económico pero preciso usted mismo construye, capaz de controlar la PCR reacciones para la detección de ADN, deterioro de la cerveza y otras aplicaciones.Tiene un costo de $499.|![](https://openpcr.org/assets/machine-34ba9a259de2ce130a96f9f6380cc9da.png)|
|Chai Open qPCR|Inicie una prueba en el laboratorio, vea los resultados desde su casa o desde cualquier lugar donde tenga Internet.O lleve Open qPCR al campo. Construido como un tanque diminuto y con un peso de sólo 4 kg, es fácil de transportar y puede funcionar en cualquier lugar donde haya energía. Tiene un costo de $5799.|![](https://www.chaibio.com/assets/products/openqPCR/chai-page/Open-qPCR-7dff2e69b70d96490b173ab6b7a1e3e3d37ad6da3d7f4d2057cf5f682151f352.webp)| 
|NinjaPCR|Más pequeño y más fácil de construir,cambia de plataforma de Adobe AIR a WiFi, casi todas las PC y teléfonos inteligentes son compatibles, todo en el navegador,mantenga la precisión de temperatura baja a alta, actualización automática para nuevas funciones (por ejemplo, soporte IFTTT programado).|![](https://camo.githubusercontent.com/a9a0cf95e2a95d366ea2541dfef33168138d7b727e7e6c9dda65e8b9240008ce/68747470733a2f2f6e696e6a617063722e746f72692e73742f6d616b65722f696d616765732f6d616b65725f616e645f6b6974352e6a7067)|
## Propuesta de Solución
***Termociclador microfluídico orientado a educación superior***
### Lista de Requerimientos
**FUNCIONALES:**
+ Replicación del ADN mediante el uso de un chip microfluídico
+ Regulación de temperatura en intervalos

**NO FUNCIONALES:**
+ Pantalla táctil
+ Capacidad de analizar una muestra
+ Ligero
+ Accesible para estudiantes
+ Interfaz guiada
## Matriz Morfológica
[![matriz-morfologica.jpg](https://i.postimg.cc/Jzw2QZvV/matriz-morfologica.jpg)](https://postimg.cc/D8g6vJ7B)
## Bibliografía

[1] Bahena-García E, García-Cordero JL. Termociclador de Bajo Costo para Amplificar DNA Mediante Técnica de PCR en Microdispositivos. MCNIB [Internet]. 2014 [citado el 31 de agosto de 2023];1(1):152–5. Recuperado de: https://memoriascnib.mx/index.php/memorias/article/view/196

[2] En M, Lenin C, De T, Avenida D, Núm M-X. Fundamentos de la reacción en cadena de la polimerasa (PCR) y de la PCR en tiempo real [Internet]. Medigraphic.com. [citado el 31 de agosto de 2023]. Recuperado de: https://www.medigraphic.com/pdfs/invdis/ir-2013/ir132d.pdf  

[3] Grupo 1A - Informe Final de Maqueta Termociclador Convencional y en Tiempo Real [Internet]. Scribd. [cited 2023 Sep 1]. Available from: https://es.scribd.com/document/650243313/Grupo-1A-Informe-Final-de-Maqueta-Termociclador-Convencional-y-en-Tiempo-Real

[4] https://patents.google.com/patent/ES2617599T3/es?q=(termociclador)&oq=termociclador

[5] https://bonsailab.com/producto/workflow/analisis-y-cuantificacion/naicasystem/

[6] https://www.medicalexpo.es/prod/microfluidic-chipshop-gmbh/product-111519-945527.html

[7] https://www.medicalexpo.es/prod/amplyus/product-107982-1043126.html

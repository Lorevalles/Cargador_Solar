# Proyecto Prius: Estación de Carga Solar

![Toyota Prius Gen 2 Plug-in Solar](https://github.com/Lorevalles/Cargador_Solar/blob/main/Imagenes/Cargando.JPG)

## Introducción
Este proyecto se enfoca en la implementación de una estación de carga solar para un Toyota Prius convertido en híbrido enchufable. Utilizando paneles solares y baterías de respaldo, el objetivo es suministrar energía limpia y renovable para la carga del vehículo.
 - [Toyota Prius convertido en híbrido enchufable.](https://github.com/Lorevalles/Proyecto_Prius/blob/main/README.md)

## Componentes Principales

### Paneles Solares
**Modelo:** [PANEL SOLAR 550W JA SOLAR MONO PERC HC JAM72S30 MR](https://www.obramat.es/panel-solar-465w-ja-solar-mono-perc-hc-25037434.html)
- **Descripción:** Paneles solares fotovoltaicos utilizados para captar la energía del sol y convertirla en electricidad.
- **Especificaciones:**
  - Potencia: 550W por panel
  - Voltaje de salida: 55V
  - Intensidad (Isc) estimada: 14A
    
### OPTIMIZADOR
- **Modelo:** [TS4-A-O TIGO](https://www.obramat.es/optimizador-ts4-a-o-tigo-10974712.html)
- **Descripción:** Mejora el rendimiento de los paneles solares, 
- **Especificaciones:**
  - Potencia: 700W por panel
  - Rango de voltaje: 16V - 80V
  - Corriente máxima: 15A
  - Potencia máxima: 700W

### Disyuntor de corriente continua
- **Modelo:** [DC MCB 63A](https://es.aliexpress.com/item/1005004593346679.html?spm=a2g0o.order_list.order_list_main.189.2631194dYLNt67&gatewayAdapt=glo2esp)
- **Descripción:** Distribuidor doble de Corriente con Interruptor 16A 250V
- **Especificaciones:**
  - Circuitos: 2
  - Voltaje: 250V
  - Protección: IP54 doble magnetotermico-diferencial

### Distribuidor de Corriente con doble Interruptor y diferncial
- **Modelo:** [Carcasa IP54 2 circuitos](https://amzn.eu/d/0hfS8EAD)
- **Descripción:** Conjunto fotovoltaico de 500V, 2 entradas, 2 salidas.
- **Especificaciones:**
  - FUSIBLE: CC 4 1000V 15A
  - Voltaje: 500V
  - Protección: MCB de CC 2 P 1000V 63A de 2 piezas

### BMS 
- **Modelo:** [QUCC QM-K621RUBL 3.7V 200A UART485CAN 6-21S](https://es.aliexpress.com/item/1005004981652594.html?spm=a2g0o.order_list.order_list_main.144.2631194dYLNt67&gatewayAdapt=glo2esp)
- **Descripción:** Protección de la batería.
- **Especificaciones:**
  - Series de batería: 6S-21S
  - Intensidad máxima: 200A
  - Voltaje de entrada: 22V/76V
  - Funcionalidades: Con NTC , bluetooth, balance, UART/RS485/CAN.
  
### Inversor de Onda Senoidal Pura
- **Modelo:** [JIANSHUN Pure Sine Wave Solar Inverter 20000W](https://amzn.eu/d/04rNMctd)
- **Descripción:** Convierte la corriente continua (DC) de los paneles solares y baterías en corriente alterna (AC) para cargar el vehículo y otros dispositivos eléctricos.
- **Especificaciones:**
  - Potencia máxima: 20000W
  - Potencia útil en continuo: 7000W
  - Voltaje de entrada: 12V/24V/48V/72V en el equipo 72V. S20 Litio.
  - Voltaje de salida: 220V/240V AC

### Controlador Solar MPPT
- **Modelo:** [MPPT Solar Controller](https://es.aliexpress.com/item/1005006140709151.html?spm=a2g0o.order_list.order_list_main.5.2631194dYLNt67&gatewayAdapt=glo2esp)
- **Descripción:** Maximiza la eficiencia de los paneles solares ajustando constantemente la carga para obtener la máxima potencia posible.
- **Especificaciones:**
  - Voltaje de entrada máximo PV: 230V
  - Voltaje de batería: 12V/24V/36V/48V/72V/84V/96V (72V. S20 Litio).
  - Corriente de carga: 60A/80A/100A (modelo 80A)

### Interruptor de circuito MCCB de CC 250V
- **Modelo:** [CC 1P DC250V](https://es.aliexpress.com/item/1005004205157391.html?spm=a2g0o.order_list.order_list_main.239.2631194dYLNt67&gatewayAdapt=glo2esp)
- **Descripción:** Protector de cortocircuito, interruptor de batería 200A
- **Especificaciones:**
  - Voltaje máximo: DC250V
  - Número de polos: 1P
  - Corriente de carga: 200A

### Baterías de Respaldo
- **Descripción:** Baterías de iones de litio utilizadas para almacenar la energía generada por los paneles solares.
- **Especificaciones:**
  - Capacidad: 18 kWh
  - Voltaje: 72V

## Procedimiento de Instalación

### 1. Instalación de los Paneles Solares
- **Ubicación:** Seleccione una ubicación con máxima exposición solar durante el día.
- **Montaje:** Fije los paneles solares en un ángulo óptimo para captar la mayor cantidad de luz solar.
- **Conexión:** Conecte los paneles solares en serie o paralelo según el diseño del sistema.

### 2. Conexión del OPTIMIZADOR
- **Montaje:** Instale el optimizador en la parte trasera de cada panel solar.
- **Conexión:** Conecte el optimizador al panel solar y al sistema de cableado del controlador MPPT.

### 3. Instalación del BMS
- **Montaje:** Monte el BMS cerca de las baterías de respaldo.
- **Conexión:** Conecte el BMS a las baterías siguiendo las instrucciones del fabricante para garantizar la correcta protección y gestión de las baterías.

### 4. Instalación del Inversor de Onda Senoidal Pura
- **Ubicación:** Coloque el inversor en un lugar ventilado para evitar el sobrecalentamiento.
- **Conexión:** Conecte el inversor a las baterías y a la red eléctrica del vehículo.

### 5. Conexión del Controlador Solar MPPT
- **Montaje:** Instale el controlador MPPT en una ubicación segura y accesible.
- **Conexión:** Conecte el controlador a los paneles solares y a las baterías para maximizar la eficiencia de carga.

### 6. Configuración y Pruebas
- **Configuración:** Configure todos los dispositivos según las especificaciones del fabricante.
- **Pruebas:** Realice pruebas iniciales para asegurarse de que todos los componentes funcionen correctamente y que el sistema esté cargando las baterías del vehículo de manera eficiente.


## Conclusión
Este proyecto demuestra la viabilidad de utilizar energía solar para cargar vehículos híbridos enchufables, promoviendo el uso de energías renovables y reduciendo la dependencia de combustibles fósiles.

## Imágenes del Proyecto

### Sistema de Paneles Solares
![Sistema de Paneles Solares](https://github.com/Lorevalles/Cargador_Solar/blob/main/Imagenes/Reales/IMG_1881.JPG)

### Inversor y Controlador Solar
![Inversor y Controlador Solar](https://github.com/Lorevalles/Cargador_Solar/blob/main/Imagenes/Reales/IMG_2094.JPG)

### Instalación Completa interior
![Instalación Completa](https://github.com/Lorevalles/Cargador_Solar/blob/main/Imagenes/Reales/IMG_2285.JPG)

### Indicador de Potencia inversor
![Indicador de Potencia](https://github.com/Lorevalles/Cargador_Solar/blob/main/Imagenes/Reales/IMG_2107.JPG)

### Potencia procedente de las placas solares
![Indicador de carga solar](https://github.com/Lorevalles/Cargador_Solar/blob/main/Imagenes/Reales/IMG_2292.PNG)

### Cuadros entradas/salidas
![Panel de conexiones exteriores](https://github.com/Lorevalles/Cargador_Solar/blob/main/Imagenes/Reales/IMG_2287.JPG)

# Ejercicios Tema 1


### 1. Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar este artículo en Infoautónomos sobre el tema.

He elegido el producto [ProLiant ML30 Gen9](https://www.mercadoactual.es/hp-servidor-proliant-hp-ml30-gen9-procesador-intel-xeon-e3.html?colabG=2&gclid=CjwKCAjw3rfOBRBJEiwAam-GsKBGlWOfqVCAEDO0Ul8a2Yu1QFeZTksD51Q5RimvqWsYheLfqbt2ahoC4KUQAvD_BwE)
Este producto esta disponible por unos 820,23€. Suponemos un valor residual de 70€.
El [Coeficiente máximo de amortización según las Tablas de Amortización](http://www.agenciatributaria.es/AEAT.internet/Inicio/_Segmentos_/Empresas_y_profesionales/Empresarios_individuales_y_profesionales/Rendimientos_de_actividades_economicas_en_el_IRPF/Regimenes_para_determinar_el_rendimiento_de_las_actividades_economicas/Estimacion_Directa_Simplificada.shtml) es del 12%

Base Amortizable = 820,23 - 70 = 750,23€


#### Para 4 años


CUOTA AMORT. ANUAL = 750,23/4 = 187,55 euros.



| Año  | Cuota de amortización  | Valor contable  |
|:----:|:-----------------------:|:------:|
|1     |0€                       |820,23€ |
|2     |187,55€                  |632,73€ |
|3     |187,55€                  |445,18€ |
|4     |187,55€                  |257,68€ |     


#### Para 7 años


CUOTA AMORT. ANUAL = 750,23/7 = 107,17 euros.



| Año  | Cuota de amortización  | Valor contable  |
|:----:|:-----------------------:|:------:|
|1     |0€                       |820,23€ |
|2     |107,17€                  |713,06€ |
|3     |107,17€                  |605,89€ |
|4     |107,17€                  |498,72€ |     
|5     |107,17€                  |391,55€ |    
|6     |107,17€                  |284,38€ |    
|7     |107,17€                  |177,21€ |    

### 2. Usando las tablas de precios de servicios de alojamiento en Internet y de proveedores de servicios en la nube, Comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.



### 3. En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?
* 2,7 GHz Intel Core i5
* Tras tratar de ejecutar los comandos, No averiguamos nada ya que nuestro pc no nos devuelve informacion.

![c1](https://github.com/Maverick94/EjerciciosIV/blob/master/tema1/img/C1.png)


### 4.
#### 1. Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok.
![c2](https://github.com/Maverick94/EjerciciosIV/blob/master/tema1/img/C2.png)

#### 2. Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios.
![c3](https://github.com/Maverick94/EjerciciosIV/blob/master/tema1/img/C3.png)

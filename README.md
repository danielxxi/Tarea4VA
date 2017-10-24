# Tarea4VA

Visualizaciones para tarea 4 de Visual Analytics Uniandes

¿Cuál ha sido el comportamiento del transporte aéreo de pasajeros en Colombia en 2017?


De acuerdo a las cifras presentadas por la Aeronáutica Civil, la dinámica del sector aéreo en Colombia ha presentado para el año 2017 un crecimiento constante en el mercado del transporte. De acuerdo con la entidad, ha crecido cinco veces más que el terrestre.

Y es que de acuerdo con el informe, sólo en el primer semestre se movilizaron 17 millones 660 mil usuarios en 2017, representando un crecimiento del 3.2% a comparación del año anterior. En el mercado aéreo internacional, el número de pasajeros movilizados tuvo un incremento en 298 mil pasajeros.
Para el despliegue de las siguientes visualizaciones, fue necesario cargar los datasets disponibles en el sitio de Aerocivil 
(http://www.aerocivil.gov.co/atencion/estadisticas-de-las-actividades-aeronauticas/bases-de-datos) en una base de datos Postgres, con el fin de agregar los datos. Estos datasets sirvieron como fuente para las visualizaciones

Hallazgos
De acuerdo al agrupamiento realizado se encomntró que definitivamente los aeropuertos de Bogotá (Aeropuerto Internacional el Dorado) y el aeropuerto José María Córdova de Rionegro, Antioquia, son los aeropuertos con más cantidad de vuelos en cuanto a destino internacionales se refiere. A nivel nacional, estos mismos aeropuertos, más Villavicencio, lideraron las cifras.
Para destinos se observa que Miami, New York, Madrid y Lima lideran la lista. Desde Sao Paulo se observa que Colombia es un destino frecuente, tal vez puede ser por aspectos inherentes a turismo-negocios, o tal vez que Colombia sea utilizado como escala para otros destinos.
En cuanto a vuelos nacionales - domésticos, La ruta Villavicencio-Puerto Carreño es protagonista frecuente de las listas. Tal vez es utilizado como puente a los Llanos orientales, o tal vez es "jalonado" por la industria petrolera, con amplia frecuencia en el sector. Se podría hacer un análisis por cantidad de pasajeros para determinar el impacto de las rutas en cuanto al total de turistas.
En cuanto a los desplegado en el Tidy tree, se observa que Londres y Madrid son las ciudades preferidas para llegar al viejo continente, tal vez se puedan conseguir tiquetes más económicos intenado ingresar por otras ciudades.

Los tipo de gráficos son una adaptación de ejemplos de Mike Bostock's.

Licence:  Released under the GNU General Public License, version 3. 

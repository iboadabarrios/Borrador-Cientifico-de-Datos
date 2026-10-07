# Perfil de un científico de datos

<div align="center">

## Ander Fernández
**Senior Data Scientist en DECIDATA** · Bilbao, País Vasco 📍

</div>

Este repositorio presenta a ***Ander Fernández***, Senior Data Scientist en DECIDATA, el científico de datos que escogimos para explicar uno de sus proyectos. Lo elegimos porque su trayectoria conecta la práctica industrial con la enseñanza: ha llevado modelos de Machine Learning a producción en proyectos reales, ha sido profesor de posgrado en Big Data y comparte lo que aprende en su blog.

Aquí encontrarás:
1. **Su perfil profesional**, extraído de su blog y su LinkedIn personal.
2. **Un proyecto suyo**, con su descripción y resultados. El proyecto que explicaremos fue ganador del **Cajamar UniversityHack 2020** y trató sobre la empresa ***BlaBlaCar***: 11 millones de datos que debían transformarse en una visualización con valor para el negocio.

> Fuentes: [anderfernandez.com](https://anderfernandez.com) y su perfil de [LinkedIn](https://www.linkedin.com/in/ander-fernandez/?isSelfProfile)

---

## Sobre Ander Fernández

Ander es una persona apasionada por los datos, con más de 6 años de experiencia en Inteligencia Artificial y Ciencia de Datos. En DECIDATA, una empresa boutique de proyectos de IA, define, supervisa y ejecuta proyectos de ML de todo tipo: detección de anomalías en carrocerías de vehículos y en procesos de atornillado, predicción del peso de pollos y mucho más.

<div align="center">

<img src="ander_fernandez.jpg" alt="Foto de Ander" width="250">

</div>

## En qué trabaja
- Diseño y entrenamiento de modelos de Machine Learning que ayudan a los clientes a lograr resultados.
- Dockerización y puesta en producción de modelos.
- Apoyo a otros data scientists para resolver dudas y escribir código más eficiente.

## Trayectoria
- **Profesor** del posgrado en Big Data de la Universidad de Deusto (2020–2023): modelos supervisados, ETL en producción, modelado de datos, integración de datos y cómo convertir datos en valor de negocio.
- **Data Scientist** en LIN3S (2019–2021): modelos en producción, análisis avanzado, A/B tests, ETL y dashboards.
- **Ganador** del Cajamar UniversityHack 2020 con el caso BlaBlaCar, el proyecto que se explicara en este repositorio.
- **Máster en Big Data & Business Intelligence** y **Grado en ADE**, Universidad de Deusto.

Idiomas que habla: Español · Euskera · Inglés

---
<div align="center">
  
# *Proyecto BlaBlacar*

</div>

## ¿Que es BlaBlacar? 

BlaBlaCar es una plataforma de viajes compartidos que conecta a conductores con asientos libres y a pasajeros que van hacia el mismo destino. Fue fundada en 2006 en Francia por Frédéric Mazzella, Nicolas Brusson y Francis Nappez, y en 2020 estaba dirigida por Brusson, cofundador y CEO desde 2016.
Su modelo es asset-light: la empresa no tiene vehículos ni conductores propios, sino que funciona como un marketplace comunitario. Con el tiempo pasó de ser solo una aplicación de carpooling (funciona como una aplicacion de viaje en carro como Uber pero compartido con mas usuarios) a ofrecer una propuesta multimodal, con BlaBlaBus para los viajes en autobús y BlaBlaLines para los trayectos cortos del día a día.

<div align="center">

![Ima_1](blablacar.jpg).

</div>

## ***Momento del boom***
<details>
  <summary> Antes del Covid-19 </summary>
    En 2019 transportó cerca de 70 millones de pasajeros entre carpooling y autobús, y sus ingresos aumentaron un 71 % respecto al año anterior. Era el líder del carpooling en Europa y tenía una presencia importante en países como Brasil, México, India, Ucrania y Rusia.
La apuesta estratégica de ese momento era consolidar la oferta multimodal, combinando coche y autobús en una sola plataforma para viajes de media y larga distancia.
</details>
<details>
<summary> Durante Pandemia </summary>
BlaBlaCar suspendió BlaBlaBus en toda Europa y, aunque mantuvo el carpooling en Francia con el visto bueno del Ministerio de Transportes, la actividad cayó a solo el 1–2 % de lo normal en BlaBlaCar y entre el 5 y el 10 % en BlaBlaLines. Durante la emergencia la empresa eliminó su comisión, bajo una lógica de ayuda mutua.
El panorama fue desigual según el país: Rusia e India prohibieron el carpooling, mientras que Brasil y México todavía permitían viajar en autobús. En Francia la plataforma se detuvo durante el confinamiento y reanudó a fines de mayo, con un solo pasajero por viaje hasta finales de junio.


</details>
<details>
<summary> Su reaccion ante la situacion </summary>
BlaBlaCar reaccionó rápido desde el inicio de la crisis: recortó costos, protegió a su equipo y se mantuvo en contacto con su comunidad. Durante el primer confinamiento lanzó además BlaBlaHelp, una aplicación gratuita de ayuda entre vecinos que permitía ofrecerse como voluntario o encontrar personas de confianza para hacer compras de primera necesidad o recoger medicamentos.
La compañía también apostó por la confianza de los usuarios, aplicando protocolos sanitarios y destacando que el carpooling reduce el número de contactos entre personas en comparación con otros medios de transporte.

</details>

<details>
<summary> Recuperacion </summary>
En abril, Brusson preparaba a sus equipos para una reanudación muy lenta, de entre 12 y 18 meses, pero desde fines de junio la demanda de pasajeros volvió con fuerza. En agosto, las solicitudes en Francia superaban en un 15 % las del verano anterior, ayudadas por las vacaciones dentro del país y por la menor oferta de trenes, autobuses y aviones. La oferta de conductores volvió algo más despacio que la demanda.
Fuera de Europa el golpe fue menor. Brasil, Mexico, India y Ucrania tuvieron restricciones menos estrictas, y en países como Rusia e India la crisis empujó la compra de pasajes de autobús en línea. Con todo, el segundo trimestre se dio por perdido y el segundo confinamiento volvió a frenar el impulso: BlaBlaBus se detuvo el 1 de noviembre y no regresaría hasta la primavera, así que la empresa volcó sus esfuerzos en el carpooling para cerrar el año.

</details>

## Resultados

El año cerró con 50 millones de pasajeros frente a unos 70 millones en 2019, lo que representó el primer año de decrecimiento de la empresa. Aun así, mantuvo más del 70 % de su actividad, un resultado notable considerando que paso por el año de cuarentena debdido al Covid'19.

| Indicador | Usuarios|
|---------|---------|
| Pasajeros 2019| 70 millones|
| Pasajeros 2020 | 50 millones|
| Varianza| -30%|
|Actividad mantenida| mas del 70% en comparacion al año anterior|

<img src="gif_stonks.gif" align="right" width="300" alt="Stonks">

Los mercados fuera de Europa, como Brasil, México, India y Ucrania, tuvieron
restricciones más flexibles, lo que llevó a que la crisis acelerara
la compra de pasajes de autobús
en línea en países como Rusia e India, donde antes la mayoría se compraba en la estación.

<br clear="right">

## ***Enseñanza para un cientifico de datos***

Este trabajo realizado por un cientifico resulta bastante pertinente debido a que, las nuevas generaciones no se confien en que sus modelos de machine learning van a funcinoar siempre, de un momento a otro pueden terminar obsoletos y tambien a no basarnos en los datos sin saber su contexto anterior del por qué estos cambiaron de esa forma.

- [x] Segmentar antes de concluir: la caída de 70 a 50 millones de pasajeros oculta casos muy distintos, como el 1–2 % de actividad en marzo frente al +15 % del verano, o Europa frente a Brasil e India.
- [x] Los modelos de demanda entrenados con datos de 2015–2019 quedaron obsoletos en semanas. La pandemia fue un cambio de régimen, no un dato atípico para eliminar, así que hay que monitorear y reentrenar.
 

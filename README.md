-Visualizador de Recursos Comunitarios — ANDHES
Herramienta de acceso a información para mujeres referentas de organizaciones territoriales en Tucumán, Argentina.
🔗 Ver dashboard en Data Studio https://datastudio.google.com/reporting/7bac5326-882d-423f-91bb-e63c02b1d64c/page/gGL9D

-Contexto
ANDHES es una organización de derechos humanos con sede en Tucumán. En el marco de su trabajo con mujeres referentas de agrupaciones barriales, se realizaron reuniones semanales a lo largo del año 2024 en las que se recopiló, de manera escrita y colectiva, información sobre recursos comunitarios disponibles en el territorio: instituciones de salud, centros de atención de adicciones, dispositivos educativos, merenderos, comedores y servicios de protección social.
El desafío era que esa información acumulada en planillas físicas se convirtiera en algo accesible y actualizado para todas las referentas y la red de referentas barriales.

-Qué hace este proyecto
Sistematiza información relevada de forma manual sobre recursos comunitarios en el Área Metropolitana de Tucumán
Geolocaliza cada servicio registrado
Presenta los datos en un visualizador interactivo accesible desde cualquier dispositivo con internet
Permite la actualización de la información constantemente

-Categorías relevadas
Salud mental
Salud
Violencia de género
Cuidados comunitarios
Administración 
Deportes
Educación
Acceso a la justicia
Comedores y merendero
Defensa ambiental
Niñez y adolescencia
Adultos mayores

-Decisiones técnicas
Las herramientas fueron elegidas con criterios concretos: acceso libre, bajo consumo de datos, facilidad de uso para personas sin experiencia técnica y posibilidad de trabajo colaborativo futuro.
Google Sheets como base de datos
Accesible sin instalación ni costo
Editable por las coordinadoras de ANDHES sin intermediarios
Permite actualizaciones en tiempo real conectadas al dashboard
Facilita el trabajo colaborativo a distancia
Data Studio (antes Looker Studio) como visualizador
Herramienta gratuita de Google
Se conecta directamente a Google Sheets sin exportaciones manuales
Interfaz legible desde celular (prioritario dado el perfil de las usuarias)
No requiere cuenta ni instalación para consultar el dashboard
Permite filtros interactivos sin conocimientos técnicos
Google Forms para actualizar
Herramienta gratuita de Google
Se puede sistematizar en un Google Sheets para su control
Accesible desde cualquier dispositivo
Permite la colaboración de datos e información para mantener actualizado o realizar sugerencias del visor

-Proceso
Relevamiento escrito en reuniones semanales
        ↓
Sistematización en Google Sheets (limpieza, categorización, geolocalización)
        ↓
Diseño del dashboard en Data Studio
        ↓
Prueba de accesibilidad con usuarias reales
        ↓
Publicación y entrega a ANDHES
        ↓
Proceso iterativo con actualización de datos de manera colaborativa

-Contenido del repositorio
/
├── README.md
├── capturas/
│   ├── dashboard_general.png
│   ├── filtro_salud.png
│   └── mapa_recursos.png

La base de datos no se publica en este repositorio para proteger la información de las instituciones y personas registradas.

-Impacto
Este visualizador centraliza en un solo lugar información que antes existía dispersa en papeles y planillas físicas, con el objetivo de que las mujeres referentas puedan:
Identificar rápidamente a qué servicio derivar una situación concreta
Acceder a datos de contacto actualizados sin depender de intermediarios
Contar con una herramienta que la propia organización puede mantener y ampliar

    Autora
Camila Agustina Mopty
 Arquitecta | Analista de Datos Geoespaciales | Doctoranda CONICET
 GitHub · camilamopty@gmail.com

Proyecto realizado de manera voluntaria en el marco del trabajo territorial de ANDHES (2024).

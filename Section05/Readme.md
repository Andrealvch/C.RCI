<div align="center"><a href="https://www.escuelaing.edu.co/es/investigacion-e-innovacion/centro-de-estudios-hidraulicos/" target="_blank"><img src="https://github.com/rcfdtools/R.TeachingResearchGuide/blob/main/CaseUse/.icons/IconCEHBanner.jpg" alt="R.LTWB" width="100%" border="0" /></a></div>

# Ejemplo diseño sistema contra incendio a base de agua 

<div align="center">
<b> Universidad Escuela Colombiana de Ingeniería Julio Garavito</b>
<br> Andrea Liseth Vasco Chivatá 
<br>  Profesor del Centro de Estudios Hidráulicos 
<br>  andrea.vasco@escuelaing.edu.co 
</div>

<br> En este módulo se presenta un ejercicio práctico de la red contra incendio a base de agua en una edificación siguiendo los lineamientos de diseño estipulados en la NFPA 13 (2019). 

El diseño para construcción de un sistema de red contra incendio generalmente inicia con la elaboración de un diseño conceptual, el cual, brinda una aproximación del sistema que se desea implantar en el área de estudio, una vez aprobado este diseño, se realizan los detalles para construcción de los elementos particulares del sistema que garantizan el adecuado funcionamiento de la red.

<br>

<div align="center">
    <a href="https://youtu.be/X0Btomi-3Mo">
        <img src="https://github.com/Andrealvch/C.RCI/blob/main/.graph/INICIO_ACTIVIDAD.PNG" width="800px">
    </a>
</div>

<br>

## Diseño conceptual del sistema de red contra incendio en la edificación

1.	Reconocer el área de estudio identificando el acceso a los servicios que permiten la instalación interna del sistema. Para este ejercicio se toma como base la implantación arquitéctonica de un edificio de 3 pisos, con una distribución tipo por piso. Cada piso cuenta con 16 espacios de oficinas, sala de reuniones, 3 bodegas, 1 comedor, 2 baños para mujeres y 2 para hombres, cuarto de aseo, sala con 8 computadores, recepción y showroom. el proyecto esta ubicado en la ciudad de Bogotá. 

<div align="center">
  <img src="https://github.com/Andrealvch/C.RCI/blob/main/Section05/.graph/Arquitectonica.png" width="1000px">
  </div>

2.	Determinar el tipo de ocupación de la edificación conforme a la clasificación de la NSR 10 en lo títulos J y K para identificar las zonas y tipos de protección. [Véase Sección 1, Normas](../Section01/Normas).

Con base en lo revisado en la sección 1, la edificación a diseñar se clasifica dentro del grupo C- Comercio, subgrupo Servicios C-1. Para esta clasificación, la norma establece los siguientes requerimientos mínimos para la protección contra incendio del edificio: 

|Grupo de ocupación|Rociadores de incendio|Tomas fijas para bomberos|Extintores portátiles|
|:------------------|:---------------------|:------------------------|:--------------------|
|Comercio|- En edificios de más de 9 metros de altura. (C-2) - Con un área mayor de 100 m2, incluidas áreas de mazanines. (C-2) - Para áreas mayores de 200 m2, que se utilicen para ventas, almacenamiento o manipulación de mercancías. (C-2) - En edificios mayores de 18 metros de altura. (C-1) [Véase Sección 2, NFPA-13](../Section02/NFPA13)|Todas las edificaciones del grupo C deben contar con un sistemas de tomas fijas, mangueras para extinción de incendios que estén a la mano del cuerpo de bomberos, según norma NFPA - 14 |Todas las edificaciones del grupo C deben estar protegidas con un sistema de extintores de incendio, según norma NFPA - 10. [Véase Sección 1, Extintores](../Section01/Extintores)|

3.	Definir el tipo de rociadores a utilizar en el edificio. De acuerdo con el diseño arquitectónico del proyecto, el sistema contra incendio a proponer quedará a la vista, es decir, los espacios de la edificación no contarán con cielo raso. Con esta información se procede a escoger un sistema de red contra incendio a base de agua junto con los rociadores colgantes de temperatura 57°C para la protección del edificio. [Véase Sección 4, Rociadores](../Section04/Rociadores). 

4.	Realizar el trazado general de las redes a partir de los criterios de localización relacionados en la norma referenciada. Verificando que todos los espacios estén cubiertos por el sistema de rociadores. En la NFPA 13 capítulo <b> "8.6.2 Áreas de Protección por Rociador (Rociadores Pulverizadores Estándar Colgantes y Montantes)" </b> la norma establece en la tabla 8.6.2.2.1(a) las áreas de protección y espaciamiento máximo de los rociadores con base en el tipo de construcción (con o sin obstrucciones) y en el tipo de riesgo de la edificación. Para la edificación del ejemplo que se considera de riesgo ligero y sin obstrucciones, la norma establece que el espaciamiento entre rociadores es de 4.6 m y 18.6 m² de área de protección. De acuerdo con esta información, se presenta el plano con la distribución de los rociadores junto con el área de influencia de cada uno para verificar que todos los espacios estén 100% cubiertos. Cabe recordar que normalmente la influencia de los rociadores es:

<div align="center">
  <img src="https://github.com/Andrealvch/C.RCI/blob/main/Section05/.graph/distribucion%20oficinas%20la%20mundial-Model.jpg" width="1300px">
  </div>

Como se puede observar en la imagen, se presenta la propuesta de ubicación de los rociadores cubriendo todos los espacios con las distancias establecidas en la norma NFPA 13.

5. Es necesario definir la ubicación de las estructuras complementarias de operación y control del sistema.

La norma NFPA 14 establece los requerimientos mínimos para la instalación de sistemas de tubería vertical y mangueras de acuerdo con la clase de sistema. Se planten los sitemas clase I, II y III, de acuerdo con los siguientes críterios: 

<b> Sistemas Clase I: </b> sistemas de tubería vertical que provee conexiones de manguera de 65 mm para suministrar agua para uso por cuerpos de bomberos.

<b> Sistemas Clase II: </b> debe proveer estaciones de manguera de 38 mm para suministrar agua para uso por cuerpo de bomberos durante la respuesta inicial. 

<b> Sistemas Clase III: </b> debe proveer estaciones de manguera de 38 mm para suministrar agua de uso personal y conexión de 65 mm para un gran volumen de agua para uso de cuerpo de bomberos. 

Cualquiera de estos sistemas deben ubicarse a no menos de 0.9 m o a más de 1.5 m sobre el piso, sin ningún tipo de obstrucción. Deben estar separados a máximo 30.5 m entre ellos y se instalan en las entradas de los corredores de evacuación. Esta implantación se replica en los tres pisos de la edificación. 

<div align="center">
  <img src="https://github.com/Andrealvch/C.RCI/blob/main/Section05/.graph/Gabinete.png" width="1300px">
  </div>

6. Es indispensable tener un espacio para instalar el sistema de operación y control de la red y elementos que complementan el sistema de extinción contra incendio. En este caso, en el plano arquitectónico se ubica el sistema de conexión de bomberos, gabinetes de incendio, extintores, panel de control de incendio y elementos de alarma de incendio en la recepción del primer piso. 

<div align="center">
  <img src="https://github.com/Andrealvch/C.RCI/blob/main/Section05/.graph/Centro%20de%20control.jpg" width="1300px">
  </div>

7.	Para iniciar con los cálculos hidráulicos, es indispensable realizar un trazado aproximado de la tubería de la red, tal como se presenta en la siguiente imagen.

<div align="center">
  <img src="https://github.com/Andrealvch/C.RCI/blob/main/Section05/.graph/Trazado.png" width="1300px">
  </div>

8.	Elaboración de las memorias de cálculo y los planos de diseño. Para esta actividad, se recomienda realizar el procedimiento descrito en la NFPA 13 capitulo 11, de la siguiente manera:

<b> Diseño para construcción </b>

A. Para determinar la demanda de agua la norma específica el método de tuberías por tablas o del cálculo hidráulico, establecido en el capitulo 11.2.2 y 11.2.3 respectivamente de la NFPA 13. Para este caso se utiliza el método de cálculo hidráulico, definiendo que el riesgo de la eidficación por su uso es Riesgo Ordinario 1. 

Para el método descrito, primero se debe revisar la gráfica de curvas Densidad/Área presentada en la NFPA 13 (Figura 19.3.3.1.1 Curvas Densidad/Área.).

<div align="center">
  <img src="https://github.com/Andrealvch/C.RCI/blob/main/Section05/.graph/Curvas%20D-A.png" width="1300px">
  </div>

Se define una densidad de agua de 0.15 GPM/ft2 para Riego Ordinario 1, para un área de operación del rociador de 1500 ft2.

B. Seleccionar el área de diseño: se recomienda verificar con el grupo de coordinación si el proyecto cuenta con muros cortafuegos o no y así poder definir la metodología de diseño que más se ajusta a las carcaterísticas del proyecto. 
Para este ejemplo, el proyecto no cuenta con muros cortafuegos y por ende la metodología que se aplicará es área-densidad. Tal como fue visto en la sección NFPA 13 sección 22, 

2.	De acuerdo con la gráfica dimensionar el sistema de red contra incendio
3.	Modelar hidráulicamente la ruta crítica del sistema
4.	Elaborar las memorias de cálculo y los planos para construcción
5.	Elaborar los documentos técnicos que permitan una operación continua del sistema especificando el detalle constructivo de cada uno de los elementos a implementar en la zona de estudio

<div align="center"><a href="https://enlace-academico.escuelaing.edu.co/psc/FORMULARIO/EMPLOYEE/SA/c/EC_LOCALIZACION_RE.LC_FRM_ADMEDCO_FL.GBL" target="_blank"><img src="https://github.com/rcfdtools/R.TeachingResearchGuide/blob/main/CaseUse/.icons/IconCEHBannerCertificado.jpg" alt="R.LTWB" width="100%" border="0" /></a></div>

##

<div align="center"><a href="http://www.escuelaing.edu.co" target="_blank"><img src="../.icons/Banner1.svg" alt="Support by" width="100%" border="0" /></a><sub><br>Este curso guía ha sido desarrollado con el apoyo de la Escuela Colombiana de Ingeniería - Julio Garavito. Encuentra más contenidos en https://github.com/uescuelaing</sub><br><br></div>

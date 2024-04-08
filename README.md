# BCN accidents 2023

### by Toni Andreu

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)

## Installation <a name="installation"></a>

The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

**We will like to study BCN traffic accidents in 2023.**

For this project,

1. Verifiying data, clean & drop undesired columns
  
2. Studying data: accidentys by district, week day, months, shift & causes.

3. Prepare data, transform categorical data to ML.

4. Look for Correlations

5. Prepare data, transform categorical data.

6. Find correlations, prepare train/test sets

7. Use linear regression model

6. Modifify to improve model & apply cross-validation.


## File Descriptions <a name="files"></a>

  1. Title: 2023_ACCIDENTS_CAUSA_CONDUCTOR_GU_BCN_.csv

  2. Sources:
    (a) Origin:  https://opendata-ajuntament.barcelona.cat/data/es/dataset/accidents_causa_conductor_gu_bcn/resource/5a040155-38b3-4b19-a4b0-c84a0618d363
    (b) Creator:  Guardia Urbana - Ajuntament de Barcelona 
    (c) Date: 08/02/2024

  3. Relevant Information:

    Accidentes según causa gestionados por la Guàrdia Urbana a la ciutat de Barcelona

  4. Number of Instances: 8897

  5. Number of Attributes: 20/4

  6. Original Attribute Information:

      01.Numero_expedient
      02.Codi_districte
      03.Nom_districte
      04.Codi_barri
      05.Nom_barri
      06.Codi_carrer
      07.Nom_carrer
      08.Num_postal
      09.Descripcio_dia_setmana
      10.NK_Any 
      11.Mes_any
      12.Nom_mes
      13.Dia_mes
      14.Hora_dia
      15.Descripcio_torn
      16.Descripcio_causa_mediata
      17.Coordenada_UTM_X_ED50
      18.Coordenada_UTM_Y_ED50
      19.Longitud_WGS84
      20.Latitud_WGS84

  7. Final Attribute Information:
    01.   Nom_districte
    02.   Mes_any
    03.   Descripcio_dia_setmana
    04.   Descripcio_torn
    05.   Descripcio_causa_mediata


## Results<a name="results"></a>

The district of Eixample has the highest number of accidents and Gracia has the least. Most of them have occured during Afternoon, followed by morning. Least accidents occured during Night time. Friday is the day with more and sunday with less. August the month with less accidents. The main cause of accidents is poor attention in driving.

Corr only shows some correlation betwween shifts, months & weekdays. We use a linear regressions model, but accuracy was low. We try to improve the model. And using cross-validation don't get better results either. Seems Linear regression is not the best model for this df!





# The Aquifer Datasets
- Auser
- Doganella
- Luco
- Petrignano  

Each aquifer has its own csv file, with different columns and rows. To continue with the best foot forward, it is important to get a grasp of how each df interacts with each other. To do so, a data dictionary for each df is shown below.

# Data Dictionaries
## Auser
Aquifer_Auser.csv, 26 columns and 8154 rows

| Feature Name          | Count | Description                                                                                                                                                                                                 | Data Type  |
|-----------------------|-------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| Date                  | 1     | DD/MM/YYYY, index ranging from 05/03/1998 to 30/06/2020                                                                                                                                                     | daily date |
| Rainfall              | 10    | Columns for rainfall in mm from areas of Gallicano, Pontetetto, Monte Serra,<br>Orentano, Borgo a Mozzano, Piaggione, Calavorno, Croce Arcana, Tereglio Coreglia <br>Antelminelli, and Fabbriche di Vallico | float      |
| Depth to Ground Water | 5     | Columns for meters to the ground floor detected by the piezometers of LT2, <br>SAL, PAG, CoS, DIEC                                                                                                          | float      |
| Temperature           | 4     | Columns for temperature from thermometric stations of Orentano, Monte Serra, <br>Ponte a Moriano, Lucca Orto Botanico                                                                                       | float      |
| Volume                | 5     | Columns for volume of water in cubic meters from drinking water treatment <br>plants of POL, CC1, CC2, CSA, CSAL                                                                                            | float      |
| Hydrometry            | 2     | Columns for ground water level in meters from hydrometric stations <br>Monte_S_Quirico, Piaggione                                                                                                           | float      |

## Doganella
Doganella_Aquifer.csv, 21 columns and 6026 rows  

| Feature Name          | Count | Description                                                                                                       | Data Type  |
|-----------------------|-------|-------------------------------------------------------------------------------------------------------------------|------------|
| Date                  | 1     | DD/MM/YYYY, index ranging from 01/01/2004 to 30/06/2020                                                           | daily date |
| Rainfall              | 2     | Columns for rainfall in mm from areas of Monteporzio, Velletri                                                    | float      |
| Depth to Ground Water | 9     | Columns for meters to the ground floor detected by the piezometers<br>of Pozzo 1-9                                | float      |
| Temperature           | 2     | Columns for temperature from thermometric stations of Monteporzio,<br>Velletri                                    | float      |
| Volume                | 8     | Columns for volume of water in cubic meters from drinking water treatment <br>plants of 1-9 with 5 and 6 combined | float      |

## Luco
Luco_Aquifer.csv, 21 columns and 7487 rows

| Feature Name          | Count | Description                                                                                                                                                                                        | Data Type  |
|-----------------------|-------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| Date                  | 1     | DD/MM/YYYY, index ranging from 01/01/2000 to 30/06/2020                                                                                                                                            | daily date |
| Rainfall              | 10    | Columns for rainfall in mm from areas of Simignano, Siena Poggio al Vento,<br>Mensano, Montalcinello, Monticiano la Pineta, Sovicille, Ponte Orgia,<br>Scorgiano, Pentolina, Monteroni Arbia Biena | float      |
| Depth to Ground Water | 4     | Columns for meters to the ground floor detected by the piezometers<br>of Podere_Casetta, Pozzo 1, Pozzo 3, Pozzo 4                                                                                 | float      |
| Temperature           | 4     | Columns for temperature from thermometric stations of Siena Poggio al Vento,<br>Mensano, Pentolina, Monteroni Arbia Biena                                                                          | float      |
| Volume                | 3     | Columns for volume of water in cubic meters from drinking water treatment <br>plants of Pozzo 1, Pozzo 3, Pozzo 4                                                                                  | float      |

## Petrignano
Petrignano_Aquifer.csv, 7 columns and 5223 rows

| Feature Name          | Count | Description                                                                                           | Data Type  |
|-----------------------|-------|-------------------------------------------------------------------------------------------------------|------------|
| Date                  | 1     | DD/MM/YYYY, index ranging from 01/01/2000 to 30/06/2020                                               | daily date |
| Rainfall              | 1     | Columns for rainfall in mm from area of Bastia Umbra                                                  | float      |
| Depth to Ground Water | 2     | Columns for meters to the ground floor detected by the piezometers of P24 and P25                     | float      |
| Temperature           | 2     | Columns for temperature from thermometric stations of Bastia Umbra and Petrignano                     | float      |
| Volume                | 1     | Columns for volume of water in cubic meters from drinking water treatment <br>plant of C10 Petrignano | float      |
| Hydrometry            | 1     | Columns for ground water level in meters from hydrometric stations <br>Fiume Chiascio Petrignano      | float      |

**drivers.csv**

| Data                                                                                                                      | Description                                                                                   | Data Type                                             |
|---------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------------------------|
| `driverId`                                                                                                                  | O número da identidade dos corredores                                                         | Dados qualitativos (polinomial não ordinal)           |
| `forename`                                                                                                                  | Nome próprio dos corredores                                                                   | Dados quantitativos (polinomial não ordinal)          |
| `Cargo`                                                                                                                  | Sobrenome dos corredores                                                                      | Dados qualitativos (polinomial não ordinal)           |

**races.csv**

| Data                                                                                                                      | Description                                                                                   | Data Type                                             |
|---------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------------------------|
| `raceId`                                                                                                                  | Número de identidade da corrida                                                               | Dados qualitativos (polinomial não ordinal)           |
| `circuitId`                                                                                                               | Idade da pessoa que respondeu à pesquisa                                                      | Dados quantitativos (discretos)                       |
| `name`                                                                                                                    | Nome da corrida                                                                               | Dados qualitativos (polinomial ordinal)               |
| `date`                                                                                                                    | Data da corrida                                                                               | Dados qualitativos (binomial simétrico)               |
| `year`                                                                                                                    | Ano da corrida                                                                                | Dados qualitativos (polinomial não ordinal)           |

**results.csv**

| Data                                                                                                                      | Description                                                                                   | Data Type                                             |
|---------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------------------------|
| `raceId`                                                                                                                  | Número de identidade da corrida                                                               | Dados qualitativos (polinomial não ordinal)           |
| `driverId`                                                                                                               | Numero da identidade dos corredores                                                      | Dados quantitativos (discretos)                       |
| `grid`                                                                                                                    | Posição inicial dos corredores                                                                               | Dados qualitativos (polinomial ordinal)               |
| `position`                                                                                                                    | Posição final dos corredores                                                                               | Dados qualitativos (binomial simétrico)               |
| `points`                                                                                                                    | Pontos recebidos na corrida                                                                                | Dados qualitativos (polinomial não ordinal)           |

# ExploratoryDataAnalysis
Simple exploration of a data set

Loading the dataset
```{r}
games <- read_csv("Data/appstore_games.csv") %>% 
          select(Name, 
                 `Average User Rating`, 
                 `User Rating Count`, 
                 Price, 
                 Developer, 
                 `Original Release Date`)  
```


<br>
<br>
<br>











# Why is $1 - \frac{1}{1 - \frac{1}{1 - ...}}$ not real?

*****************************

So we all know that the continued fraction containing all 1 s...

$$x = 1 + \frac{1}{1 + \frac{1}{1 + ...}}$$

yields the golden ratio $x =\phi$, which can easily be proven by rewriting it as $x = 1 + 1/x$, ...












<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<br>
<br>
<br>









# Why are these numbers unequal?

*****************************

The following code is obviously wrong. What's the problem?


```
i <- 0.1
i <- i + 0.05
i
## [1] 0.15
if(i==0.15) cat("i equals 0.15") else cat("i does not equal 0.15")
## i does not equal 0.15
```













<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>









## Options d'affichage


Code source et sortie

```r
  (i <- 5)
```

```
## [1] 5
```




--------------------

Code source

```r
  (i <- 5)
```

--------------------

Sortie

```
## [1] 5
```



















## Analyse de l'objet R `cars` 

En premier lieu, un aperçu graphique de la distance en fonction de la vitesse :

```
plot(cars)
```

![](C:\Users\Laurent\Documents\GitHub\OTC\images\img_car_plot.jpeg)















<br>
<br>
<br>
<br>










## Analyse de l'objet R `cars` 

En premier lieu, un aperçu graphique de la distance en fonction de la vitesse :


```r
plot(cars)
```

![](HTML_Outputs_files/figure-html/unnamed-chunk-4-1.png)




















<br>
<br>
<br>
<br>
<br>




# Première solution



Voici le tableau des résultats :

```
##                           J1          J2           J3           J4
## Nombre.de.gains  4829.750000 1723.250000 1697.0830000 1749.9170000
## Prob.de.victoire    0.482975    0.172325    0.1697083    0.1749917
```

On constate que ...

### Code source ayant produit cette sortie : 
    Voici le tableau des résultats :
    ```{r}
      resultats
    ```
    
    On constate que ...
    
# Deuxième solution

Voici le tableau des résultats :

Table: Tableau 2 : Gains et probs ...

                             J1            J2             J3             J4
-----------------  ------------  ------------  -------------  -------------
Nombre.de.gains     4829.750000   1723.250000   1697.0830000   1749.9170000
Prob.de.victoire       0.482975      0.172325      0.1697083      0.1749917

On constate que ...

### Code source ayant produit ce résultat :

    Voici le tableau des résultats :
    ```{r}
      knitr::kable(resultats, caption = "Tableau 2 : Gains et probs ...")
    ```
    
    On constate que ...

<p>a. Como foi a definição da sua estratégia de modelagem?</p>

<p>A a minha definição foi encontrar quais são as variaveis mais importantes e principais para o modelo de classificação room_type.</p>

<p>b. Como foi definida a função de custo utilizada?</p>
  
<p>c. Qual foi o critério utilizado na seleção do modelo final?</p>

<p>A escolha do modelo apropriado, do ponto de vista estatístico.</p>

<p>d. Qual foi o critério utilizado para validação do modelo?</p>

<p>O criterio foi verficar a acuracia baseado na sensibilidade e especificidade usando a validação confusion matrix.</p>

<p>e. Por que escolheu utilizar este método?</p>

<p>O modelo K-Nearest Neighbors apresentou melhores resultados apartir da sua accuracy e sensibilidade.</p>

<p>f. Quais evidências você possui de que seu modelo é suficientemente bom?</p>

<p>Overall Statistics
<p>   
<p>  Accuracy : 0.7758         
<p>   95% CI : (0.763, 0.7883)
<p>   No Information Rate : 0.7487         
<p>   P-Value [Acc > NIR] : 0.00002057     
<p>                                         
<p>                 Kappa : 0.3711         
<p>                                         
<p>Mcnemar's Test P-Value : NA             
<p>
<p>Statistics by Class:
<p>
<p>   Class: Entire home/apt Class: Hotel room
<p>Sensitivity                          0.8939         0.0526316
<p>Specificity                          0.4737         0.9988160
<p>Pos Pred Value                       0.8350         0.1666667
<p>Neg Pred Value                       0.5998         0.9957507
<p>Prevalence                           0.7487         0.0044790
<p>Detection Rate                       0.6693         0.0002357
<p>Detection Prevalence                 0.8015         0.0014144
<p>Balanced Accuracy                    0.6838         0.5257238
<p>  Class: Private room Class: Shared room
<p>Sensitivity                       0.4462           0.222222
<p>Specificity                       0.8886           0.994964</p>
<p>
<p>#Evidencias para um modelo satisfatório 
<p>Accuracy       : 0.7758  
<p>Sensitivity    : 0.8939
<p>Specificity    : 0.4737

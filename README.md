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
   
   Accuracy : 0.7758         
   95% CI : (0.763, 0.7883)
   No Information Rate : 0.7487         
   P-Value [Acc > NIR] : 0.00002057     
                                         
                  Kappa : 0.3711         
                                         
 Mcnemar's Test P-Value : NA             

Statistics by Class:

   Class: Entire home/apt Class: Hotel room
Sensitivity                          0.8939         0.0526316
Specificity                          0.4737         0.9988160
Pos Pred Value                       0.8350         0.1666667
Neg Pred Value                       0.5998         0.9957507
Prevalence                           0.7487         0.0044790
Detection Rate                       0.6693         0.0002357
Detection Prevalence                 0.8015         0.0014144
Balanced Accuracy                    0.6838         0.5257238
  Class: Private room Class: Shared room
Sensitivity                       0.4462           0.222222
Specificity                       0.8886           0.994964</p>

<p>#Evidencias para um modelo satisfatório 
Accuracy       : 0.7758  
Sensitivity    : 0.8939
Specificity    : 0.4737 </p>

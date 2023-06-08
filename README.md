# Работа с гистонами

HGNC approved symbol: **ASH1L**

Product: H3K36me

Fucntion: Histone modification write

Protein complex: #

Pfam domains: BAH, PHD, SET, Bromodomain (BAH PF01426 2661-2798, Bromodomain PF00439 2453-2538, PHD PF00628 2587-2631, Pfam-B_14208 PB014208 1818-1847, Pfam-B_18246 PB018246 2310-2419, Pfam-B_25586 PB025586 1473-1507, Pfam-B_4663 PB004663 1023-1054 1180-1377, Pfam-B_6310 PB006310 1509-1554, SET PF00856 2156-2261)

\
[Crystal Structure of the Human Histone Methyltransferase **ASH1L** Catalytic Domain and Its Implications for the Regulatory Mechanism](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3048721/):
> This observation is also consistent with the notion that hASH1L specifically methylates H3K36

\
[Trithorax-group protein **ASH1** methylates histone H3 lysine 36](https://doi.org/10.1016%2Fj.gene.2007.04.027)

[**ASH1L** Links Histone H3 Lysine 36 di-methylation to MLL Leukemia](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4930721/)

[Histone H3K36me2-Specific Methyltransferase **ASH1L** Promotes MLL-AF9-Induced Leukemogenesis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8534482/)

ASH1L относится к группе транскрипционных активаторов Trithorax. 
Он локализуется в мелких пятнышках в ядре, а также в межклеточных контактах. 

Заболевания, связанные с ASH1L включают нарушение интеллектуального развития и различные виды рака (лейкемия, неходжкинская лимфома и другие).

Экспрессируется в различных тканях, в основном в мозге, яичниках и щитовидной железе.
![gene-exp-plot (2)](https://github.com/LadyPython/hse23_project/assets/6313540/d50b521c-eb41-4178-974e-ece883e70c5f)


## Выравнивания (MEGAX)

### H2A
Есть 2 ярковыраженные группы: 1-13 и 23-41, они являются копиями. Остальные немного отличаются.
![image](https://github.com/LadyPython/hse23_project/assets/6313540/d4c3b3b0-a5e9-44e6-aad1-2d34fbbc0570)

### H2B
Гены 2-20 являются копиями, остальные незначительно отличаются.
![image](https://github.com/LadyPython/hse23_project/assets/6313540/8fab1aab-7aed-42fc-a57a-226e44b51df1)

### H3
Гены являются копиями.
![image](https://github.com/LadyPython/hse23_project/assets/6313540/21673f22-0964-4a33-a49c-80f2deaf55a3)

### H4
Гены являются копиями.
![image](https://github.com/LadyPython/hse23_project/assets/6313540/124677b4-2c84-40b9-8b67-ef5e9c7ceb4f)

## E-value

|index|C\.ELEGANS|METHA...|MOUSE|HUMAN|THE...|YEAST|DROSOPHILA|TUB...|E\.COLI|CILIATE|ZEBRAFISH|
|---|---|---|---|---|---|---|---|---|---|---|---|
|H2A|9\.21e-66|0\.000491|3\.8e-89|2\.07e-89|0\.003|1\.82e-63|2\.89e-68|0\.45|1\.3|2\.97e-57|5\.78e-82|
|H2B|5\.98e-66|1\.7|1\.95e-88|2\.78e-88|1\.2|1\.01e-60|2\.75e-60|2\.3|1\.6|4\.62e-51|1\.86e-83|
|H3|4\.46e-94|0\.034|1\.54e-96|2\.19e-96|0\.057|3\.31e-87|9\.39e-96|4\.6|1\.0|8\.41e-86|1\.77e-95|
|H4|6\.15e-68|8\.22e-05|7\.6e-68|1\.09e-67|3\.31e-05|1\.08e-52|8\.02e-68|0\.069|1\.0|1\.96e-45|1\.13e-68|
|ASH1L|9\.7e-38|0\.36|1e-300|1e-300|0\.067|4\.19e-39|1e-300|7\.8|1\.0|2\.54e-34|1e-300|

### -log10(E-value)

|index|C\.ELEGANS|TUBERCULOSIS|DROSOPHILA|THERMOCOCCUS|METHANOCALDOCOCCUS|HUMAN|YEAST|CILIATE|ZEBRAFISH|MOUSE|E\.COLI|
|---|---|---|---|---|---|---|---|---|---|---|---|
|H2A|65\.03574036980315|0\.3467874862246563|67\.53910215724345|2\.5228787452803374|3\.3089185078770313|88\.68402965454308|62\.73992861201493|56\.52724355068279|81\.23807216157947|88\.4202164033832|-0\.11394335230683678|
|H2B|65\.22329881601159|-0\.36172783601759284|59\.56066730616974|-0\.07918124604762482|-0\.2304489213782739|87\.55595520408193|59\.995678626217355|50\.33535802444388|82\.73048705578208|87\.70996538863749|-0\.20411998265592482|
|H3|93\.35066514128786|-0\.6627578316815741|95\.02733440773389|1\.2441251443275085|1\.4685210829577449|95\.65955588515988|86\.48017200622428|85\.07520400420209|94\.75202673363819|95\.81247927916354|-0\.0|
|H4|67\.21112488422459|1\.1611509092627446|67\.09582563171584|4\.480172006224281|4\.0851281824599495|66\.96257350205937|51\.96657624451305|44\.707743928643524|67\.94692155651659|67\.11918640771921|-0\.0|
|ASH1L|37\.01322826573376|-0\.8920946026904804|300\.0|1\.1739251972991736|0\.44369749923271273|300\.0|38\.3777859770337|33\.59516628338006|300\.0|300\.0|-0\.0|

### Тепловая карта (log10)
![image](https://github.com/LadyPython/hse23_project/assets/6313540/0ae30f7d-70cd-49a4-858a-c4fbeab6c705)

Появилась в одноклеточных эукариотах (ciliate) и закрепилась в эволюции.



# TripleHypothesisR
W projekcie badam trzy hipotezy dotyczące zależności między danymi klinicznymi pacjentów a posiadaniem przez nich zespołu metabolicznego. Analiza opiera się na modelowaniu statystycznym w języku R, wykorzystując informacje demograficzne oraz kliniczne. 


Dane wykorzystane w projekcie pochodzą z platformy Kaggle: 

https://www.kaggle.com/datasets/antimoni/metabolic-syndrome


Hipotezy badawcze:

**Hipoteza 1**: Model przewidujący poziom HDL oparty na jego 2 najlepszych predyktorach będzie lepiej dopasowany do danych, niż te bazujące tylko na jednym z nich.

**Hipoteza 2**: Przewidując poziom *glukozy* we krwi za pomocą modelu z interakcją wskaźnika BMI oraz informacji nt. posiadania *dyslipidemi aterogennej*, otrzymamy lepiej dopasowany model, niż model bez interakcji.

**Hipoteza 3**: Istnieją istotne różnice w obowdzie w talii, przewidzianym za pomocą BMI między osobami, które mają *syndrom metaboliczy*, a tymi, które nie mają tego syndromu.

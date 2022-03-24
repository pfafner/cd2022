# Introducción a la Ciencia de Datos 2022

Este es un curso introductorio a la ciencia de datos, con énfasis principalmente en los fundamentos matemáticos y estadísticos de los principales algoritmos de aprendizaje automático y reconocimiento de patrones. El tema central del curso es el estudio de métodos para obtener información útil a partir de datos. Al final del curso, los estudiantes comprederán, tanto en la teoría como en la práctica, las etapas necesarias para producir un estudio o análisis de datos, desde la concepción de un problema, hasta la generación de un informe técnico de análisis. Para aprovechar de mejor manera el curso, es recomendable que los estudiantes estén familiarizados con temas de álgebra lineal, cálculo, estadística matemática, y tener conocimientos de al menos un lenguaje de programación (*e.g.* Python, R, Matlab, C++, u otros).


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-cd2022.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Lunes y miércoles, 17:20 a 18:55 horas.  Laboratorio: a definir.

### Office Hours
<div id='id-office'/>

* Viernes de 18:00 a 20:00 horas, o por solicitud del estudiante. También pueden enviar sus dudas por correo electrónico.


# Material del curso
<div id='id-material'/>

  **No.**  | **Fecha**    | **Tópicos**                                                         | **Actividades**
  -------- | ------------ | ------------------------------------------------------------------- |  -------------------------------------
  01       | 10.01.2022   | Introducción <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"}    | [(I. Carmichael, J.S. Marron) Data Science vs. Statistics: Two Cultures?](lecturas/carmichael_marron.pdf){:target="_blank"}
  02       | 12.01.2022   | Repaso de probabilidad I: espacios de probabilidad. <br/> [Aula 02](aulas/Aula02.pdf){:target="_blank"} | Ver Chung, Capítulo 1.
  03       | 17.01.2022   | Probabilidad condicional <br/> [Aula 03](aulas/Aula03.pdf){:target="_blank"} | Ver Lefebvre, capítulo 2, pp. 27--5  44
  04       | 19.01.2022   | Ley de probabilidad total. Regla de Bayes. <br/> [Aula 04](aulas/Aula04.pdf){:target="_blank"} | Lefebvre, capítulo 2, pp. 27--54.
  05       | 24.01.2022   | Repaso de probabilidad II: variables aleatorias. <br/> [Aula 05](aulas/Aula05.pdf){:target="_blank"} | Lefebvre, sección 3.1, pp. 55–60.
  06       | 26.01.2022   | Independencia de v.a. Resúmenes de distribuciones. <br/> [Aula 06](aulas/Aula06.pdf){:target="_blank"} | Lefebvre, sección 3.2, pp. 61–69.
  L1       | 29.01.2022   |                                                                     | **[Lista de ejercicios 1](listas/lista01.pdf){:target="_blank"}** <br/> **Fecha de entrega: Sábado 12 de febrero.**
  07       | 31.01.2022   | Esperanza condicional. Covarianza y correlación. Entropía. <br/> [Aula 07](aulas/Aula07.pdf){:target="_blank"} | 
  08       | 02.02.2022   | Distribuciones Discretas. Resúmenes para distribuciones continuas. <br/> [Aula 08](aulas/Aula08.pdf){:target="_blank"} | Lefevbre, sección 3.3.
  09       | 02.02.2022   | Distribuciones Continuas. Distribuciones multivariadas. <br/> [Aula 09](aulas/Aula09.pdf){:target="_blank"} | Material sobre v.a. continuas y resúmenes de distribuciones. <br/> Lefebvre, sección 3.3, pp. 70–80.
  10       | 07.02.2022   | Análisis de Componentes Principales (PCA). <br/> [Aula 10](aulas/Aula10.pdf){:target="_blank"} | Duda y Hart, sección 10.13.1, pp. 568-.
  11       | 09.02.2022   | PCA vs. Teorema Espectral y descomposición SVD. <br/> [Aula 11](aulas/Aula11.pdf){:target="_blank"} [Aula 11 notas](aulas/Aula11_notas.pdf){:target="_blank"} | Hastie, Tibshirani, Friedman, sección 14.5.
  12       | 14.02.2022   | Proyección PCA. Ejemplos. <br/> [Aula 11 notas](aulas/Aula12_notas.pdf){:target="_blank"} | 
  13       | 16.02.2022   | Interpretación PCA. <br/> [Aula 12](aulas/Aula12.pdf){:target="_blank"} |
  14       | 21.02.2022   | Escalamiento multidimensional. <br/> [Aula 13](aulas/Aula13.pdf){:target="_blank"} |
  15       | 23.02.2022   | PCA Robusto y extensiones PCA. <br/> [Aula 14](aulas/Aula14.pdf){:target="_blank"} |
  L2       | 27.02.2022   |                                                                     |  **[Lista de ejercicios 2](listas/lista02.pdf){:target="_blank"}** <br/> [crimes.dat](listas/crimes.dat){:target="_blank"} [weather.csv](listas/weather.csv){:target="_blank"} <br/> **Fecha de entrega: Sábado 12 de marzo.**
  16       | 02.03.2022   | Kernel PCA. Ejemplos de transformaciones no-lineales. <br/> [Aula 15](aulas/Aula15.pdf){:target="_blank"} |
  17       | 07.03.2022   | ICA (Análisis de componentes independientes). NNMF. <br/> [Aula 16](aulas/Aula16.pdf){:target="_blank"} |
  18       | 09.03.2022   | Métodos Locales I: Isomap, t-SNE, LLE, SOM. <br/> [Aula 17](aulas/Aula17.pdf){:target="_blank"} | Más ejemplos de visualizaciones con SOM [Minisom](https://github.com/JustGlowing/minisom/tree/master/examples){:target="_blank"}
  19       | 14.03.2022   | Métodos Locales II: Spectral Embedding, Autoencoders, Prob. PCA, Projection-Pursuit. <br/> [Aula 18](aulas/Aula18.pdf){:target="_blank"} | Software para visualización de datos. Contiene una implementación de projection pursuit. <br/> [http://ggobi.org/](http://ggobi.org/){:target="_blank"}
  20       | 16.03.2022   | Estimación empírica de distribuciones. <br/> [Aula 19](aulas/Aula19.pdf){:target="_blank"} | 
  L3       | 19.03.2022   |                                                                     |  **[Lista de ejercicios 3](listas/lista03.pdf){:target="_blank"}** <br/> [hpi-data-2016.xlsx](listas/hpi-data-2016.xlsx){:target="_blank"} <br/> **Fecha de entrega: Domingo 03 de abril.**
  21       | 21.03.2022   | Técnicas de visualización. <br/>                                    | [visualisation.ipynb](code/visualisation.ipynb){:target="_blank"}
  22       | 23.03.2022   | Imputación de datos. <br/> [Aula 21](aulas/Aula21.pdf){:target="_blank"} | [imputation.ipynb](code/imputation.ipynb){:target="_blank"} [hpi-data-2016.csv](code/hpi-data-2016.csv){:target="_blank"} 
  
  
# Material adicional (scripts)
<div id='id-labs'/>

  **No.**  | **Fecha**    | **Tópicos**                                                         | **Material**
  -------- | ------------ | ------------------------------------------------------------------- |  -------------------------------------
  00       | 02.02.2022   | Instalación de librerías y ambiente de trabajo Python Anaconda, Jupyter-lab.  | [Anaconda+Tensorflow+Jupyter installation guide](otros/Anaconda+Tensorflow+Jupyter_installation_guide.pdf){:target="_blank"} <br/> *Archivos auxiliares:* [plotmatrix.py](otros/plotmatrix.py){:target="_blank"} [test.ipynb](otros/test.ipynb){:target="_blank"}
  01       | 07.02.2022   | Ejemplo de exploración de datos.                                    | [iris.ipynb](code/iris.ipynb){:target="_blank"}
  02       | 14.02.2022   | Lectura archivo csv. Exploración de datos. Estandarización. Descomposición SVD. Análisis de componentes principales. | [pca.ipynb](code/pca.ipynb){:target="_blank"} <br/> [deport.csv](code/deport.csv){:target="_blank"}
  03       |              | Ejemplo de escalamiento multidimensional.                           | 
  04       | 07.03.2022   | Ejemplos de ICA.                                                    | [ica_examples.ipynb](code/ICA_examples.ipynb){:target="_blank"} <br/> [horse.jpg](code/horse.jpg){:target="_blank"} [morro.jpg](code/morro.jpg){:target="_blank"} [plane.jpg](code/plane.jpg){:target="_blank"} [race.jpg](code/race.jpg){:target="_blank"}
  05       | 07.03.2022   | Ejemplo de NNMF.                                                    | [nnmf.ipynb](code/nnmf.ipynb){:target="_blank"}
  06       | 09.03.2022   | Ejemplos de *Manifold Learning*.                                    | [manifold.ipynb](code/manifold.ipynb){:target="_blank"}
  07       | 14.03.2022   | Ejemplo de SOM.                                                     | [democracy_index.csv](code/democracy_index.csv){:target="_blank"} [democracy_index_som.ipynb](code/democracy_index_som.ipynb){:target="_blank"}
  08       | 16.03.2022   | Ejemplos de distribución empírica por kernel.                       | [1D-kernel-density.ipynb](code/1D-kernel-density.ipynb){:target="_blank"} [2D-kernel-density.ipynb](code/2D-kernel-density.ipynb){:target="_blank"}



# Primer Proyecto
<div id='id-labs'/>

Análisis de datos de EcoBici. <br/>
Recursos: <br/>
Sitio web oficial de EcoBici [https://www.ecobici.cdmx.gob.mx/](https://www.ecobici.cdmx.gob.mx/){:target="_blank"} <br/>
Datos abiertos [https://www.ecobici.cdmx.gob.mx/es/informacion-del-servicio/open-data](https://www.ecobici.cdmx.gob.mx/es/informacion-del-servicio/open-data){:target="_blank"}


  **No.**  | **Fecha**    | **Tópicos**                                                         | **Material**
  -------- | ------------ | ------------------------------------------------------------------- |  -------------------------------------
  P1       | 16.03.2022   | Primer proyecto <br/> [Proyecto 1](proyecto/proyecto1.pdf){:target="_blank"} | Coordenadas de estaciones <br/> [stations.json](proyecto/stations.json){:target="_blank"} [stations.csv](proyecto/stations.csv){:target="_blank"}  
  .        | 18.04.2022   | Presentaciones                                                      | 
  .        | 20.04.2022   | Presentaciones                                                      | 
  .        | 21.04.2022   | Entrega del reporte, código y presentación.                         | 
  
  

# Material sobre Python (textos, videos)
<div id='id-python'/>

* [R. Gonzáles Duque. *Python para todos*.](lecturas/Python_para_todos.pdf){:target="_blank"}

* [Theodore Petrou. *Pandas Cookbook*.](lecturas/Pandas_Cookbook.pdf){:target="_blank"}

* [*Curso Python (Youtube)*.](https://www.youtube.com/watch?v=G2FCfQj-9ig&list=PLU8oAlHdN5BlvPxziopYZRd55pdqFwkeS){:target="_blank"}


# Referencias
<div id='id-ref'/>

### Textos:

* [R. Duda, P. Hart, D. Stork (2000). *Pattern classification*.](http://library.lol/main/5858DCFE63D714C5C42F433D5F821631){:target="_blank"}

* [C. Bishop (2000). *Pattern Recognition and Machine Learning*.](http://library.lol/main/B616EF565E2D48AE23EE2E19D7B0ADD2){:target="_blank"}

* [T. Hastie, R. Tibshirani, J. Friedman (2013). *The Elements of Statistical Learning*.](http://library.lol/main/5F88A9F135B7AB31FBCF1729412560DC){:target="_blank"}

* [K. Murphy (2012). *Machine Learning: a Probabilistic Perspective*.](http://library.lol/main/8ECFEEB2E1F9A19C770FBA1FF85FA566){:target="_blank"}

### Referencias adicionales:

* [K.-L. Chung (2000). *A Course in Probability Theory*](http://library.lol/main/6B122D4F68618DB5F1893F0296CB2491){:target="_blank"}

* [M. Lefebvre (2011). *Basic Probability with Applications*](http://library.lol/main/F3B9314CA31E0289D5FCD6EEDA01308A){:target="_blank"}

* [G. James, D. Witten, T. Hastie, R. Tibshirani (2008). *An Introduction to Statistical Learning with Applications in R*.](http://library.lol/main/1E48B8220FEE4CD9D192F4ED5020F2DA){:target="_blank"}

* [A. Izenman (2008). *Modern Multivariate Statistical Techniques: Regression, Classification and Manifold Learning*.](http://library.lol/main/B5E1DA4CD9133B468CA730402BBC7117){:target="_blank"}

* [B. Everitt, T. Hothorn (2011). *An Introduction to Applied Multivariate Analysis with R*](http://library.lol/main/83BD38DABC018FE79C6AEEF726BF20D7){:target="_blank"}

* [K. Fukunaga (1990). *Introduction to Statistical Pattern Recognition*.](http://library.lol/main/F1FC9B38F5E9F245C7CDE3AFEDED4D06){:target="_blank"}

* [C. Giraud (2015). *Introduction to High-Dimensional Statistics*.](http://library.lol/main/38E216C9EFA26C09F5A2324BC3122F92){:target="_blank"}

* [L. Devroye, L. Györfi, G. Lugosi (1996). *A Probabilistic Theory of Pattern Recognition*.](http://library.lol/main/60F75D016A9C96D67D752536B9D1753A){:target="_blank"}

* [S. Shalev-Shwartz, S. Ben-David (2014). *Understanding Machine Learning: From Theory to Algorithms*.](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf){:target="_blank"}

* [P. Rigollet (2015). *Mathematics for Machine Learning*.](https://ocw.mit.edu/courses/mathematics/18-657-mathematics-of-machine-learning-fall-2015/lecture-notes/MIT18_657F15_LecNote.pdf){:target="_blank"}

### Artículos:

* [A. S. Bandeira (2016). *Ten Lectures and Forty-Two Open Problems in the Mathematics of Data Science*.](https://people.math.ethz.ch/~abandeira/TenLecturesFortyTwoProblems.pdf){:target="_blank"}

---

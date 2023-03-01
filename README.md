# G8-Turkey_Energy_Consumptions
- G8 ülkeleri ve Türkiye Enerji Tüketimleri Enerjide Kullanılan Maddelerin Payları İncelenmiştir.
Bu proje Tübitak araştırma önerimizin kabul edilmemesi sonucu üzerine hayata geçirilmeye çalışılmıştır.
Herhangi bir bütçe desteği olmadan mümkün koşullar altında Tübitak önerimizin ana hatlarından çıkmadan önerimizdeki yöntemlerin birkaç tanesi kullanılarak konudan sapmadan bazı değişikliklere uğratılıp tamamlanılmıştır.


Proje özetle veri bilimi teknikleriyle elimizdeki ham veri setlerini işe yarar hale getirmek, gelecek yıllar hakkında tahminlerde bulunmak ve ülkeleri belli bir başarı sırasına koymaya yarayacak, ileriki yıllarda yapılacak başka projeler için zemin hazırlayacaktır.

Çalışma #python dilinde #jupyternotebook kullanılarak, veri işleme için #pandas, veri görselleştirme için #numpy, analiz için NumPy uzantısı olan #matplotlib kütüphaneleri kullanılacaktır.

Kullanılan kütüphaneler:

import pandas  <br>            
import seaborn   <br>          
import numpy               
import matplotlib.pyplot   
from sklearn                        import tree
from sklearn                        import metrics
from sklearn.tree                   import DecisionTreeClassifier 
from sklearn.model_selection        import train_test_split
from sklearn.preprocessing          import StandardScaler
from sklearn.metrics                import confusion_matrix
from sklearn                        import utils
from sklearn.linear_model           import LinearRegression
from sklearn.linear_model           import LogisticRegression
from sklearn.neighbors              import KNeighborsClassifier
from sklearn.discriminant_analysis  import LinearDiscriminantAnalysis
from sklearn.naive_bayes            import GaussianNB
from sklearn.svm                    import SVC
from sklearn.model_selection        import cross_val_score
from sklearn.cluster                import KMeans
from sklearn.metrics                import r2_score, mean_absolute_error, mean_squared_error

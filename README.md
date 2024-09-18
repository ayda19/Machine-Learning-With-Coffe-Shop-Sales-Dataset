
# Machine Learning with Medical Chatbot Dataset                     
  
# Projenin Amacı
Projenin amacı hasta il doktorlar arası iletişimi kolaylaştırmak , hastanın şikayetleri üzerine daha kolay tanı konulup uygun tedavi yöteminin bulunmasında yardımıcı olmaktır .

# Veri Seti
Bu veri seti 256916 satır ve 3 sütundan oluşmaktadır .
Temelde doktorlar ve hastalar arasındaki konuşmaların transkripsiyonlarını içerir ve tıbbi konsültasyonların dinamiklerine dair değerli içgörüler sunar. Çeşitli tıbbi durumları, hasta endişelerini ve tedavi tartışmalarını kapsayan geniş bir etkileşim yelpazesi içerir. Veriler, hem hastaların gündeme getirdiği soruları ve endişeleri hem de doktorların sağladığı tıbbi tavsiyeleri, teşhisleri ve açıklamaları yakalamak üzere yapılandırılmıştır. 

***Sütun isimleri şu aşağıdaki gibidir :***
- Description
- Patient
- Doctor

**Veri setimizin temel özellikleri**
  
***Doktor ve Hasta Rolleri***: Her görüşme, konuşmacının (doktor veya hasta) rolüyle açıklanarak iletişim kalıplarının analiz edilmesi kolaylaştırılmıştır.
  
***Tıbbi Bağlam*** : Veri seti, rutin kontrollerden daha karmaşık tıbbi tartışmalara kadar çeşitli senaryoları içererek geniş bir yelpazede sağlık diyalogları sunmaktadır.

***Doğal Dil***: Konuşmalar doğal dilde sunulmakta ve bu sayede sağlık iletişimine odaklı NLP modellerinin geliştirilmesi ve test edilmesi mümkün olmaktadır.

***Uygulamalar***: Bu veri seti, diyalog sistemleri oluşturma, iletişim etkinliğini analiz etme, tıbbi NLP modelleri geliştirme ve doktor-hasta etkileşimlerinin daha iyi anlaşılması yoluyla hasta bakımını geliştirme gibi çeşitli uygulamalar için kullanılabilir.





# Değişkenler

import random

import time

from sklearn.model_selection import train_test_split

import sklearn.preprocessing as LabelEndcoder 

import sklearn.preprocessing as PolynomialFeatures

import seaborn as sns

from xgboost import XGBRegressor

from sklearn import linear_model , tree

from sklearn.metrics import mean_squared_error , r2_score

from datetime import datetime 

from statsmodels.stats.outliers_influence import variance_inflation_factor

from joblib import Parallel , delayed

from sklearn.pipeline import Pipeline



# Model Seçimi








# Veri setimin dosya boyutu büyük olduğu için yükleyemedim . Bu nedenle aşağıya linklini bırakıyorum .
https://www.kaggle.com/datasets/yousefsaeedian/ai-medical-chatbot/data?select=ai-medical-chatbot.csv#:~:text=calendar_view_week-,ai%2Dmedical%2Dchatbot.csv,-Summary

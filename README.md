# Teknofest Doğal Dil İşleme
#Acıkhack2024TDDİ
#İçerikMuhafızı

# NLP_Dataset
Bu repo İçerik Muhafızı takımımızın bert tabanlı model eğitiminde kullanılan veri setini ve eğitilen modelin nasıl kullanılacağını içerir.

# Model Kullanımı 
from transformers import AutoModelForSequenceClassification, AutoTokenizer

model_name = "IcerikMuhafizi/bert-base-turkish-uncased-IM3"

model = AutoModelForSequenceClassification.from_pretrained(model_name)
tokenizer = AutoTokenizer.from_pretrained(model_name)

# Arayüz

![Açıklama Metni](https://github.com/icerikMuhafizi/IcerikMuhafizi-TeknofestTDDI-2024/blob/main/png_a)
![Açıklama Metni](https://github.com/icerikMuhafizi/IcerikMuhafizi-TeknofestTDDI-2024/blob/main/png1)
![Açıklama Metni](https://github.com/icerikMuhafizi/IcerikMuhafizi-TeknofestTDDI-2024/blob/main/png_m?raw=true)


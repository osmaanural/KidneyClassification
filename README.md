# KidneyClassification
🔔  Derin Öğrenme ile Böbrek Hastalıklarının Sınıflandırılması: Tümör, Kist, Taş ve Normal Dokular

Sağlıkta yapay zeka uygulamalarına olan ilgim doğrultusunda, son dönemde kendi geliştirdiğim bir derin öğrenme projesini daha tamamladım.

💡 Problem:

 BT görüntülerinde böbreklerde görülen dört farklı durumu (tümör, kist, taş ve normal doku) ayırt edebilen bir model oluşturmak. Bu tür bir sınıflandırma, klinik karar destek sistemleri için büyük önem taşıyor.

Kendi geliştirdiğim CNN mimarisini kullanarak veri setini doğrudan işledim.

Eğitim sürecinde early stopping stratejisi uyguladım; böylece modeli gereksiz epochlarda çalıştırmadan aşırı öğrenmeyi (overfitting) engelledim.

Modeli CrossEntropyLoss ile eğittim ve sınıfları tümör, kist, taş ve normal olacak şekilde etiketledim.

 Sonuçlar:

 Test Doğruluğu: %100

 Precision / Recall / F1-Score: 1.00

Karışıklık matrisi: 4 sınıfta da kusursuz sınıflandırma

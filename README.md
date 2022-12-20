### Yolov5

- 1.Adım (Dataset bulma)
	Nesneleri tanımak için bir datasete ihtiyacımız var herhangi bir data set bulmalıyız(bu örnekte maske dataseti kullanılmıştır. Siz istediğinizi yapabilirsiniz.
	Dataset bulmak için çeşitli sitelerden elde edilebilir veya kendimiz de oluşturabiliriz (ki bu pek kolay değil)
	Bunun için [kaggle](https://www.kaggle.com/) sitesini kullanabiliriz. İstediğimiz dataseti aratalım ve indirelim.
	
- 2.Adım (Dataset etiketleme)
	Datasetimiz etiketleme işlemi için roboflow.com sitesini kullanabiliriz.
	
- 3.Adım (Eğitim ve test)
	Oluşturduğumuz dataseti eğitmek için google colab kullanacağız.[Colab](https://colab.research.google.com/github/roboflow-ai/yolov5-custom-training-tutorial/blob/main/yolov5-custom-training.ipynb)
	bu siteye girdikten sonra Step 1 çalıştırıyoruz.
	Step 2 için roboflow.com dan apikey almalıyız.
	Project > Version sayfasına gidip Export butonuna basıyoruz.
	YOLO v5 PyTorch seçiyoruz show download code seçtikten sonra apikey gözükecektir
	
	Step 3 çalıştırıp eğitime başlayabiliriz. (epoch, batch ve volov5 sürümlerini değiştirebilirsiniz.)
	![](https://raw.githubusercontent.com/lBLEDAl/Notlar/main/Resimler/masked-unmasked/3.png?token=GHSAT0AAAAAAB4TH2PLXZ2QNSDNVBD4V3OIY5CES5A)
- Eğitim işlemi bittikten performans grafikleri için Evaluate Custom YOLOv5 Detector Performance Satırını
	Test için Run Inference With Trained Weights Satırını çalıştırabilirsiniz.
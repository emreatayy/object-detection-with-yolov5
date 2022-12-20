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

ENG
- Step 1 (Finding Dataset)
We need a dataset to recognize objects we need to find any dataset (in this example mask dataset is used. You can do whatever you want.
Dataset can be obtained from various sites or we can create it ourselves (which is not very easy)
We can use [kaggle](https://www.kaggle.com/) for this. Let's search for the dataset we want and download it.

- Step 2 (Dataset tagging)
We can use roboflow.com site for labeling our dataset.

- Step 3 (Training and testing)
We will use google colab to train the dataset we created.[Colab](https://colab.research.google.com/github/roboflow-ai/yolov5-custom-training-tutorial/blob/main/yolov5-custom-training.ipynb)
After entering this site, we run Step 1.
For step 2 we need to get apikey from roboflow.com.
We go to the Project > Version page and press the Export button.
We choose YOLO v5 PyTorch, after selecting show download code, apikey will appear

	We can run step 3 and start training. (You can change the epoch, batch and volov5 versions.)
![](https://raw.githubusercontent.com/lBLEDAl/Notes/main/Images/masked-unmasked/3.png?token=GHSAT0AAAAAAB4TH2PLXZ2QNSDNVBD4V3OIY5CES5A)

- Evaluate Custom YOLOv5 Detector Performance Line for performance graphs after the training process is finished
You can run the Run Inference With Trained Weights Line for testing.
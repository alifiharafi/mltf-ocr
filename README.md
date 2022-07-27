# Proyek mltf-ocr
Machine Learning with TensorFlow - OCR (Optical Character Recognition).
Repositori ini bertujuan untuk menyediakan deliverables Demo Day pada kegiatan pelatihan DTS Machine Learning with TensorFlow 2022.

## Intro
Kelompok OCR_1 masih memiliki pemahaman yang terbatas untuk kasus OCR, sehingga perlu dilakukan eksplorasi terlebih dahulu untuk bisa memahami proses end-to-end mulai dari persiapan dataset, sampai dengan memperoleh hasilnya. Aktivitas yang dilakukan saat ini masih dominan melakukan eksplorasi proyek-proyek terkait yang telah ada, sehingga belum menghasilkan proyek sesuai dengan spesifikasi yang diajukan pada proposal.

## Dataset
Dataset ditentukan oleh instruktur (OCR.zip), berupa dataset kumpulan invoice yang terdiri dari data image dengan ekstensi TIF dan hasil ekstraksi dalam format XML. Dataset tersebut selain bisa diperoleh dari Google Drive yang dibagikan oleh instruktur, juga dapat diperoleh dari:
https://www.kaggle.com/code/manishthem/entity-recognition-for-ocr-using-text-data-xml/data

## Eksplorasi
Pada repositori ini kami mencoba mengumpulkan proyek-proyek hasil eksplorasi yang bisa dilakukan oleh seluruh anggota kelompok dalam waktu yang terbatas, mulai dari:
1. Eksplorasi proyek yang terkait dengan sumber dataset [OCR_1_Spacy_Kaggle.ipynb](OCR_1_Spacy_Kaggle.ipynb). Pada hasil eksplorasi ini kami masih belum menggunakan TensorFlow, lebih menekankan pada pemahaman karakteristik dataset utama. 
2. Eksplorasi proyek dengan dataset MNIST (OCR_1_DL_MNIST.ipynb). Eksplorasi ini sudah mencoba menggunakan TensorFlow, namun belum menggunakan dataset yang disediakan oleh instruktur, melainkan menggunakan dataset MNIST. Tujuannya untuk lebih memahami terlebih dahulu bagaimana cara menggunakan TensorFlow dengan studi kasus yang mendekati dan lebih sederhana, yaitu Digit Recognition.
3. Eksplorasi TensorFlow (OCR_1_Keras_OCR.ipynb). Eksplorasi ini bertujuan untuk memperoleh gambaran utuh perkiraan hasil yang akan dicapai dengan contoh data uji sesuai dataset yang diberikan instruktur. Untuk mempermudah melihat gambaran hasil akhir, kami mencoba untuk menggunakan pre-trained model yang sudah disediakan oleh Keras OCR.
4. Eksplorasi TensorFlow (OCR_1_Keras_OCR_Custom.ipynb). Tahap eksplorasi akhir yang bisa dilakukan yaitu mencoba melakukan kostumisasi Keras OCR, melanjutkan dengan perlahan dari hasil eksplorasi sebelumnya. Namun, karena keterbatasan waktu, khususnya pada saat proses training yang paling banyak memakan waktu karena perlu melakukan epoch sampai ribuan, serta dengan terbatasnya sumber daya dengan penggunaan GPU pada Google Colab Free, aktivitas eksplorasi ini hanya bisa dilakukan sampai 50%.

## Capaian
1. Mengetahui karakteristik dan kompleksitas dataset. Dataset yang kelompok kami peroleh adalah hasil pemindaian fisik yang keterbacaannya sangat terbatas (terkadang ada karakter yang tidak begitu jelas) dan kemiringan area atau kertas hasil pemindaian mempengaruhi bentuk karakter pada gambar hasil pemindaian.
2. Memperoleh gambaran end-to-end bagaimana proses OCR invoice dapat dilakukan pada eksplorasi tahap ketiga: OCR_1_Keras_OCR.ipynb
3. Wawasan gambaran utuh perkiraan hasil dapat dicapai, walaupun masih menggunakan pre-trained model. Hal ini tentu bukan capaian akhir yang harus diserahkan karena belum sesuai dengan ketentuan dan spesifikasi yang diusulkan pada proposal. Namun, setidaknya memberikan gambaran hal-hal apa saja yang telah dilakukan dengan menyediakan catatan hasil eksplorasi.

## Presentasi
Tautan Video Presentasi: https://youtu.be/i-FWjF3Hknc 

## Referensi
https://www.kaggle.com/code/manishthem/entity-recognition-for-ocr-using-text-data-xml
https://www.kaggle.com/code/manishthem/entity-recognition-for-ocr-using-text-data-xml/data
https://github.com/Madhan13K/OCR_Character_Recognition/blob/main/OCR_character_detection.ipynb
https://colab.research.google.com/drive/19dGKong-LraUG3wYlJuPCquemJ13NN8R#scrollTo=dkU6eM05Yx1V


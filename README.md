# Overview
Convolutional Neural Networks (CNN) merupakan salah satu pilar utama dalam kemajuan Deep Learning untuk pengolahan citra dan video. Jika CNN klasik hanya mengandalkan convolution layer berlapis sederhana (misalnya pada LeNet atau AlexNet), maka Modern CNN hadir dengan arsitektur yang lebih kompleks, efisien, dan adaptif.
# Karakterisitk CNN KLasik
1. Struktur sederhana dan berurutan (conv, pooling, fully connected)
2. Banyak parameter
3. Fokus pada kedalaman (depth)
4. Cenderung sulit dilatih
# Arsitektur CNN Klasik
1. LeNet-5 (1998)
   <ul><li>Digunakan untuk pengenalan angka tulisan tangan (handwritten digit recognition).</li>
  <li>Pionir dalam membuktikan CNN bisa bekerja untuk pengolahan citra.</li> </ul>
2. AlexNet (2012)
<ul><li>CNN Menang di kompetisi Imagenet</li>
<li>Memperkenalkan ReLU dan dropout untuk mempercepat training dan mengurangi overfitting.</li></ul>
3. VGGNet (2014)
<ul><li>dengan filter kecil (3×3)</li>
  <li>parameter yang sangat besar (138 juta).</li></ul>
  
# Keterbatasan CNN Klasik
<ul><li>Boros memori dan komputasi.</li>
<li>Sulit scale up untuk dataset besar dengan resolusi tinggi.</li>
<li>Mudah menghadapi masalah vanishing gradient.</li>
<li>Tidak efisien untuk deployment pada perangkat terbatas (mobile, IoT).</li>
</ul>

# Modern CNN
Generasi baru CNN yang membawa inovasi arsitektur untuk mengatasi beberapa keterbatasan CNN Klasik

# Arsitektur CNN MOdern
1. GoogLeNet / Inception(2014)-->modular & efisien.
   <br>paper publikasi | contoh kasus dengan google colab 
2. ResNet (2015)-->jaringan sangat dalam dengan skip connection.
   <br>paper publikasi | contoh kasus dengan google colab 
3. DenseNet(2017)-->koneksi padat antar layer.
 <br>paper publikasi | contoh kasus dengan google colab  
4. MobileNet, Xception(2017)-->Depthwise Separable Convolution
   <br>paper publikasi | contoh kasus dengan google colab 
5. (EfficientNet, 2019)
    <br> paper publikasi | contoh kasus dengan google colab 
6. Attention Mechanism (SE-Net, CBAM, ECA)
7. Transformer




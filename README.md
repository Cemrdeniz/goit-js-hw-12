# API KEY KULLANARAK JAVASCRIPT İSLEMLERİ
- Kullanıcı formu gönderdiğinde (submit eventi), önce arama sorgusunu alıyorum ve boşsa işlem yapmıyorum.

-Daha önceki arama sonuçlarını temizliyorum ve yükleniyor göstergesini açıyorum.

-Axios ile Pixabay API’sine istek gönderiyorum. Burada async/await kullanarak kodun okunabilir ve yönetilebilir olmasını sağlıyorum.

-API’den dönen sonuçları alıp, her bir resmi kart olarak oluşturup .gallery içine yerleştiriyorum.

-Eğer sonuç yoksa kullanıcıya iziToast ile hata mesajı gösteriyorum.

-“Load more” butonunun görünürlüğünü kontrol ediyorum: Eğer daha fazla sonuç varsa butonu gösteriyorum, yoksa gizliyorum.

-Ayrıca, resimlerin üzerine tıklandığında açılan ışık kutusu (SimpleLightbox) kurulumu ve yenilenmesini sağlıyorum.

-Yükleme işlemi bittiğinde, yükleniyor göstergesini gizliyorum.

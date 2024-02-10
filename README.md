<img width="1284" alt="amazon" src="https://github.com/melisacevik/Amazon-Projects/assets/113050206/93623f27-5165-4d59-bfe1-151241a9945a">

# Amazon Ürün Puanlaması ve Yorum Sıralaması

## İş Problemi

E-ticarette en önemli sorunlardan biri, ürünlere verilen puanların doğru şekilde hesaplanmasıdır. Bu sorunun çözülmesi, e-ticaret siteleri için müşteri memnuniyetini artırırken, satıcılar için ürünlerinin daha fazla dikkat çekmesini ve alıcılar için sorunsuz bir alışveriş deneyimi sağlamayı içerir. Bir diğer önemli sorun ise ürünlere verilen yorumların doğru bir şekilde sıralanmasıdır. Yanıltıcı yorumların öne çıkması, ürün satışlarını doğrudan etkileyebilir, bu da hem maddi kayıplara hem de müşteri kaybına neden olabilir. Bu iki temel sorunun çözülmesi, e-ticaret siteleri ve satıcıları için satışları artırırken, müşterilerin sorunsuz bir alışveriş deneyimi yaşamasını sağlar.

## Veri Seti Hikayesi

Bu veri seti, Amazon ürün verilerini içerir ve çeşitli ürün kategorileri ile ilişkili metadataları içerir. Veri seti içerisinde en fazla yoruma sahip olan elektronik kategorisindeki ürünlerin kullanıcı puanları ve yorumları bulunmaktadır.

### Değişkenler:
- reviewerID: Kullanıcı ID’si
- asin: Ürün ID’si
- reviewerName: Kullanıcı Adı
- helpful: Faydalı derecelendirme
- reviewText: İnceleme metni
- overall: Ürün derecesi
- summary: İnceleme özeti
- unixReviewTime: İnceleme zamanı (Unix formatında)
- reviewTime: İnceleme zamanı (Raw)
- day_diff: İncelemeden bu yana geçen gün sayısı
- helpful_yes: Faydalı bulunan inceleme sayısı
- total_vote: İncelemeye verilen toplam oy sayısı

## Görevler

### Görev 1: Average Rating'i Güncel Yorumlara Göre Hesaplayınız ve Var Olan Average Rating ile Kıyaslayınız.

### Görev 2: Ürün için Ürün Detay Sayfasında Görüntülenecek 20 Review'i Belirleyiniz.

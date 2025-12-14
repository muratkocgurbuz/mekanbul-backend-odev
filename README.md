**Canlı Demo:** [https://mekanbul-backend-odev-gamma.vercel.app/](https://mekanbul-backend-odev-gamma.vercel.app/)

## 📌 Kısa Açıklama
* API, mekan (venue) verilerini yönetir: listeleme, ekleme, görüntüleme, güncelleme ve silme.
* Veritabanı olarak **MongoDB Cloud** kullanır.
* Backend servisi **Vercel** üzerinde çalışmaktadır.


API Endpoints

Tüm Mekanları listele: GET /api/venues
Yeni Mekan Ekle: POST /api/venues
Mekan Detayını Getir: GET /api/venues/:venueid
Mekanı Güncelle: PUT /api/venues/:venueid
Mekanı Sil: DELETE /api/venues/:venueid
Yorum Ekle(Mekana): POST /api/venues/:venueid/comments
Yorum Getir: GET /api/venues/:venueid/comments/:commentid
Yorum Güncelle: PUT /api/venues/:venueid/comments/:commentid
Yorum Sil: DELETE /api/venues/:venueid/comments/:commentid

Postman Test Sonucu Aşağıda Postman ile alınmış test sonuçlarının ekran görüntüsü bulunmaktadır.

Add Venue.PNG
List Nearby Venues.PNG
Get Venue.PNG
Update Vanue.PNG
Add Comment.PNG
Get comment.PNG
Update Comment.PNG
Delete Comment.PNG
Delete Vanue.PNG

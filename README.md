### Crud App
- (CREATE READ UPTADE DELETE)
- npm i uuid | import et.
- projeye boostrap dahil et.

- 1 form içerisinden gelen verileri alsın ve state aktar.
    - - Ekle butonuna tıklanınca formdan gelen kitap ismiyle yeni bir obje oluştur.
    - - değerleri : ekleme tarihi | kitap ismi | id | okuduMU
    - - oluşan objeyi kitaplar isminde bir diziyi tutan state aktardık.
    - - inputlar temizlendi.

- 2 books statetinde tutulan kitapları al ve map methodu ile ekrana yazdır.
  - - eğer state boşsa ekrana "henüz kitap eklenmedi yaz"
  - - bookcard bileşenine kitap bilgilerini prop olarak gönder.
  - -bookcard bileşenine kitapla ilgili bütün özl göster.
  
- 3 kitap silme
  - - herhangi bir kitabı silecek fonk çalıştır ve id çalıştır `handleModal`
  - - id için onay penceresi aç vazgeçe tıklanırsa kapat `setShowModal(false)`
  - - onaylanırsa silecek id ye eşit olmayanlarla yeni bir dizi oluştur
  - - oluşan yeni diziye state aktaar. `handleDeelte()`
  - - modal oluştur bir kaç yerde kullanabilirsin diye companantin içinde oluşturdum


- 4 okundu olarak işaretleme
  - - okundu butonuna tıklanınca çalışan fonk. kitabın değerlerini gönder.
  - -kitabın İsRead değerini tersine çevir.
  - - dizi içerisinde değişecek elemanı bul.
  - - değişecek elemanı çıkar yerine güncel halini ekle.
  - - state güncelle.
 

- 5 Düzenleme işlemini aktif etme
  - - düzenleye tıklanıldığında fonk. çalışsın.
  - - düzenlenecek kitabı state aktar ve modalı aç
  - - modalda --> kitap ismini değiştirmke için bir input olacak. (value= kitap ismi)
  - - Input her değiştirdiğinde düzenlenecek elemanı tuttuğun stateti güncelle.
  - - vazgeç butonu > modalı kapat
  - - kaydet tıklanırsa --> `handleEditBook` fonks çalıştırsın
  - - çalışan fonk kitaplar dizine güncellesin 
  - - güncellerken isim ve date değiştir 

- 6 bildirmler için
  - - react toastify kur.
  - - npm i react-toastify
  - - import et kendi sitesinde -->index.js de#   C r u d A p p 
 
 

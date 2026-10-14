# İcra Takip — Makrolu Boş Şablon

Excel 2016/2019 masaüstü için beş sayfa: GÜVENLİK, HOUSE, TEMİZLİK, BİTEN, ÇIKAN. Personel ve ödeme verileri boş bırakılmıştır.

1. Dosyayı indirip Excel ile açın ve bu dosyanın makrolarını etkinleştirin. Windows dosyayı engelliyorsa dosya Özellikler bölümünde Engellemeyi kaldır seçeneğini kullanın. Genel makro güvenliği ayarlarını düşürmeyin.
2. İlgili operasyon sayfasında 7. satırdan itibaren kayıt girin. Ad soyad, dosya numarası ve toplam borç tamamlandığında kayıtlar Türkçe alfabetik sıraya, aynı isimler icra sırasına göre yerleşir. TC, dosya numarası ve IBAN metin olarak tutulur.
3. 1. sıra açık mavi, sonraki sıralar açık amberdir. Kalan tutar = toplam borç − aylık ödemeler − önceki ödemeler. Nafaka bilgi alanıdır; ayrıca ödeme kaydı girilmeden borçtan düşülmez.
4. Aylar Ağustos 2026–Temmuz 2028 dönemini kapsar. Gizli yıl gruplarını üstteki + işaretleriyle açabilirsiniz. Önceki dönem toplam ödemeleri ilgili alana girilir.
5. Kaydın satırını seçip üstteki BİTEN'e aktar / ÇIKAN'a aktar düğmesini ya da satır sonundaki bağlantıyı kullanın. Onaydan sonra bütün kayıt arşive kopyalanıp alanlar doğrulanır; kaynak satır kaldırılır ve liste sıralanır. Operasyon ve aktarım tarihi arşivde görünür. Borcu kalan kayıt BİTEN'e aktarılmaz.
6. Yanlış aktarımı hemen Ctrl+Z ile geri alabilirsiniz. Tebliğ tarihi, takip tarihi, sonraki işlem ve açıklama alanlarını dosyanın takibi için kullanın.

Kontrol: Beş sayfanın boş olduğu, gömülü VBA kaynakları ve dosya yapısı doğrulandı. Örnek ödeme hesapları LibreOffice hesap motorunda beş sayfada kontrol edildi. Microsoft Excel bu ortamda bulunmadığından VBA'nın Excel içindeki çalışması doğrulanamadı. Gerçek kayıtlarınızı girmeden önce iki örnek kayıtla sıralama ve iki aktarım düğmesini kontrol edin.

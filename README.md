# Reset Devresi
Reset Devresi, butona basıldıktan belirli bir süre sonra, sistemi resetlemek amacıyla yapılmıştır. Bir mikrodenetleyicinin reset pinine uygulanan sinyal ‘0’ olunca programın çalışması başlangıç adresine döner. Sinyal ‘1’ olduğunda  program tekrar çalışır. Bu devre için direnç, diyot, kapasitör ve buton kullanılmıştır. Süre hesabı için kullanılan formül
 ’t = -log((V-Vc)/V)R*C’ dir. Bu formül referans alındığında direnç x oranında artarken kapasitörün değeri aynı x oranında azalırsa veya çıkış ve giriş voltaj değerleri aynı oranda değişirse resetleme süresi değiştirmeyecektir. 

Örneğin; 

Giriş voltajı(V): 10 V

Çıkış voltajı(Vc): 8 V

Direnç: 100 KOhm

Kapasitör: 10 uF


Süre:1609.4379 milisaniye

————————————

Giriş voltajı(V): 5 V

Çıkış voltajı(Vc):  4 V

Direnç: 10 KOhm

Kapasitör: 100 uF


Süre:1609.4379 milisaniye


İki örnekte de resetleme süresi aynıdır.



**UYGULAMA ÖRNEKLERİ:**

Giriş voltajı(V): 1.8 V

Çıkış voltajı(Vc):  1.52 V

Direnç: 10 KOhm

Kapasitör: 10 uF

Ölçülen Süre: 1.97 saniye

Formülden Hesaplanan Süre: 1.8 saniye

——————————————————

Giriş voltajı(V): 3.3 V

Çıkış voltajı(Vc):  2.4 V

Direnç: 10 KOhm

Kapasitör: 10 uF


Ölçülen Süre: 2.1 saniye

Formülden Hesaplanan Süre: 2.01 saniye


———————————————————


Giriş voltajı(V): 5.0 V

Çıkış voltajı(Vc):  4.4 V

Direnç: 10 KOhm

Kapasitör: 10 uF


Ölçülen Süre: 1.9 saniye

Formülden Hesaplanan Süre: 2.12 saniye

———————————————————

Giriş voltajı(V): 5.0 V

Çıkış voltajı(Vc):  4.4 V

Direnç: 10 KOhm

Kapasitör: 0.01 uF

Ölçülen Süre: 300 milisaniye

Formülden Hesaplanan Süre: 0.212 milisaniye

—————————————————————

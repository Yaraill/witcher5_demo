# witcher5_demo
Pygame ile yardım alarak yazdığım ilk 2D oyun
# Witcher 5 Demo: Basit Bir 2D Koşu Oyunu Prototipi

---

Bu depo, oyun geliştirme hedeflerim doğrultusunda Pygame ile geliştirdiğim **basit bir 2D koşu oyunu prototipini** içermektedir. "Witcher 5" ismi, projeye eklenen mizahi bir dokunuş olup, oyunun Pygame'in sunduğu temel mekanikleri kullanarak oluşturulmuş, engellerden kaçma tabanlı bir koşu oyunu olduğunu belirtmek isterim.

Bu proje, temel oyun döngüsü, sprite (oyuncu ve engel) yönetimi, animasyon, yer çekimi uygulaması, çarpışma tespiti ve basit bir puanlama sistemi gibi Pygame'in temel özelliklerini anlamak ve pratik etmek amacıyla yapılmıştır.

## İçerik

* **`witcher5_demo.py`**: Oyuncu karakterin zıplayarak engellerden kaçtığı, zamana karşı puan topladığı temel 2D koşu oyunu kodları.

## Nasıl Çalışır?

* **Karakter Hareketi:** Oyuncu (player) otomatik olarak ileri doğru koşar. **Boşluk tuşuna** basarak zıplar.
* **Engeller:** Salyangozlar ve sinekler gibi düşmanlar rastgele aralıklarla ekranda belirir ve sola doğru ilerler.
* **Çarpışma:** Oyuncu bir engele çarparsa oyun biter.
* **Puanlama:** Oyun aktif olduğu sürece zaman bazlı puan kazanılır.
* **Oyun Durumları:** Oyun başlangıç/tanıtım ekranı, oyun içi aktif durum ve oyun sonu ekranı olmak üzere farklı durumlar arasında geçiş yapar.

## Kullanım

Projeyi yerel bilgisayarınızda çalıştırmak için **Python** ve **Pygame** kütüphanesinin kurulu olması gerekmektedir.

1.  Depoyu bilgisayarınıza klonlayın:
    ```bash
    git clone [https://github.com/Yaraill/witcher5_demo.git](https://github.com/Yaraill/witcher5_demo.git)
    ```
2.  Proje dizinine gidin:
    ```bash
    cd witcher5_demo
    ```
3.  Pygame kütüphanesini kurun (eğer kurulu değilse):
    ```bash
    pip install pygame
    ```
4.  `witcher5_demo.py` dosyasını çalıştırın:
    ```bash
    python witcher5_demo.py
    ```

## Amaç

Bu proje, oyun geliştirme alanına olan ilgimi somutlaştırmak ve Pygame gibi bir kütüphane ile temel oyun mantığını oluşturma becerimi sergilemek amacıyla hazırlanmıştır. Gelecekte daha kompleks oyun projeleri geliştirmek için sağlam bir temel oluşturmaktadır.

## Gelecek Hedefleri

İleriki hedeflerim doğrultusunda bu tür prototip ve demo projelerle deneyimimi artırmayı sürdürüyorum.

---

## İletişim

Sorularınız, geri bildirimleriniz veya işbirlikleri için benimle iletişime geçmekten çekinmeyin:

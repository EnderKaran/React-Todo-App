# Basit Yapılacaklar Listesi Uygulaması (React)

Bu proje, React kullanarak oluşturulmuş basit bir yapılacaklar listesi uygulamasıdır. Kullanıcıların görevler eklemesine ve silmesine olanak tanır.

## Özellikler

*   **Görev Ekleme:** Yeni görevler oluşturabilirsiniz.
*   **Görev Silme:** Mevcut görevleri listeden kaldırabilirsiniz.
*   **Basit Arayüz:** Kullanımı kolay ve anlaşılır bir arayüze sahiptir.

## Teknolojiler

*   **React:** Kullanıcı arayüzü geliştirmek için kullanılan JavaScript kütüphanesi.
*   **JavaScript (ES6+):** Uygulama mantığı için kullanılan programlama dili.
*   **CSS:** Uygulama stilini düzenlemek için kullanılan stil dili. (App.css ve muhtemelen diğer bileşenlerin CSS dosyaları)
*   **Material UI Icons:**  Arayüzde ikonlar kullanmak için kullanılan Material UI kütüphanesi. (Özellikle `AssignmentIcon` kullanılıyor)
*   **Bootstrap:**  Arayüzün daha hızlı ve duyarlı bir şekilde geliştirilmesi için kullanılan CSS framework'ü. (Özellikle buton ve grid sistemleri için kullanılıyor olabilir)

## Kurulum

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

1.  **Depoyu klonlayın:**

    ```bash
    git clone [https://github.com/EnderKaran/React-Todo-App]
    ```

2.  **Bağımlılıkları yükleyin:**

    ```bash
    npm install  # veya yarn install
    ```
    **Not:** Projede Material UI Icons ve Bootstrap kullanıldığı için, eğer `package.json` dosyasında yoksa, Material UI için `npm install @mui/icons-material @mui/material @emotion/react @emotion/styled` ve Bootstrap için `npm install bootstrap` komutunu çalıştırmanız gerekebilir.

3.  **Uygulamayı başlatın:**

    ```bash
    npm start    # veya yarn start
    ```

    Bu komut uygulamayı geliştirme modunda başlatacak ve genellikle tarayıcınızda `http://localhost:3000` adresinde açılacaktır.

## Kullanım

Uygulama başlatıldıktan sonra, aşağıdaki adımları izleyerek kullanabilirsiniz:

1.  **Görev Oluşturma:** Sayfanın üst kısmında bulunan "Yeni Görev Ekle" alanına görevin başlığını ve içeriğini girin. Ardından "Ekle" düğmesine tıklayarak görevi listeye ekleyin.
2.  **Görevleri Görüntüleme:** Eklenen görevler liste halinde görüntülenecektir. Her görev başlığı ve içeriğiyle birlikte listelenir. **Görevler, Bootstrap grid sistemi sayesinde düzenli bir şekilde yan yana sıralanır (ekran boyutuna göre).**
3.  **Görev Silme:** Her görevin yanında bulunan "Sil" düğmesine tıklayarak görevi listeden kaldırabilirsiniz.

## Ekran Görüntüsü
![Ekran Görüntüsü 1](Ekran%20görüntüsü%202025-03-02%20174448.png)

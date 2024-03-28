# hotel_backend Project Link :
https://joker-hotel-front.vercel.app/


Bu proje, hotel_backend için geliştirilmekte olan bir Django backend uygulamasıdır. Aşağıda proje ile ilgili temel bilgiler ve nasıl başlayabileceğiniz hakkında bilgiler bulabilirsiniz.

## Başlangıç

Projenin çalıştırılması için Python ve Django kurulu olmalıdır. Virtual environment kullanmanız önerilir.

1. Proje dosyalarını bilgisayarınıza klonlayın.
2. Virtual environment oluşturun:

    ```
    python -m venv venv
    ```

3. Virtual environment'ı etkinleştirin:

    - Windows:

        ```
        venv\Scripts\activate
        ```

    - Linux/MacOS:

        ```
        source venv/bin/activate
        ```

4. Gerekli Python paketlerini yükleyin:

    ```
    pip install -r requirements.txt
    ```

5. Veritabanı migrations'larını uygulayın:

    ```
    python manage.py migrate
    ```

6. Geliştirme sunucusunu başlatın:

    ```
    python manage.py runserver
    ```

Tarayıcınızda https://hotel-backend-aed0e92deeca.herokuapp.com/ adresine giderek uygulamayı görebilirsiniz.

## Kullanılan Teknolojiler

- Python
- Django
- Django REST Framework

## Katkıda Bulunma

1. Bu projeyi kendi bilgisayarınıza klonlayın.
2. Yeni bir özellik ekleyin veya hata düzeltin.
3. Değişiklikleri commit'leyin ve bir pull request açın.


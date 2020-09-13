English:


KOCAELI UNIVERSITY COMPUTER ENGINEERING ANNOUNCEMENTS TRACKER. 


In order for this app to work, you should have an info.json file in the code's directory.
This is what it looks like:

    {
        "email": {
            "username": "email-username", 
            "password": "email-password", 
            "receivers": [
                "receiver1",
                "receiver2",
                "receiver3"
            ],
            "host": "host address like smtp-relay.gmail.com",
            "port": 465 (or some other port)
        }
    }

Control for new announcements takes place once every 5 minutes.

The receivers will be notified when there are new announcements or if there are any changes to the previous announcements.

An SSL connection is used to connect to email server.

How To Use: After you create and edit the info.json and install required packages, run the program with the command "python3 main.py" for Linux or "python main.py" for Windows.


------------------------------------------------------------------------------------------------------------------------


Türkçe:


KOCAELİ ÜNİVERSİTESİ BİLGİSAYAR MÜHENDİSLİĞİ BÖLÜM DUYURULARI TAKİP UYGULAMASI


Bu uygulamanın çalışması için kodun bulunduğu dizinde bir info.json dosyası olmalıdır. Bu dosya şu şekilde olmalıdır:

    {
        "email": {
            "username": "email-adresi",
            "password": "email--şifresi",
            "receivers": [
                "alıcı1",
                "alıcı2",
                "alıcı3"
            ],
            "host": "smtp-relay.gmail.com gibi host adresi",
            "port": 465 (veya başka bir port)
        }
    }

Yeni duyurular her 5 dakikada bir kontrol edilmektedir.

Alıcılar yeni duyurular için bilgilendirildiği gibi eski duyurularda bir değişiklik olduğunda da bilgilendirilmektedir.

Email sunucusuna bağlantı SSL ile yapılmaktadır.

Nasıl kullanılır: info.json dosyasını oluşturup düzenledikten ve gerekli modülleri kurduktan sonra Linux'ta "python3 main.py", Windows'ta "python3 main.py" komutuyla çalıştırabilirsiniz.
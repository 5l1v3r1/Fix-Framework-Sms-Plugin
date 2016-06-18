# Fix-Framework-Sms-Plugin
Fix Framework Sms Plugin


# TUTORIAL

      // Api Bağlı Sistem
      https://www.iletimerkezi.com/
      http://toplusmsapi.com/
 
        $this->model("iletimerkezi/iletimerkezi");

        $var = new iletimerkezi();

        $var->params = array(
            "username"      => "KULLANICI ADI",
            "password"      => "ŞİFRENİZ",
            "text"          => "GÖNDERECEĞİNİZ MESAJ",
            "receipents"    => "GÖNDERİLECEK NUMARALAR VİRGÜL İLE AYRINIZ",
            "sender"        => "KAYITLI MESAJ BAŞLIGI",

        );

        $var->sender();


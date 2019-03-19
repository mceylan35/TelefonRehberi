Kapsam
• Sistem iki farklı arayüze sahip olacaktır.
• Herkese açık arayüz (bundan sonra PublicUI olarak adlandırılacaktır)
• Sadece Admin tarafından girilebilen arayüz (bundan sonra AdminUI olarak adlandırılacaktır)
• Çalışanın ad, soyad, telefon, departman ve yönetici bilgileri sistemde yer alacaktır.
• PublicUI sadece sistemde kayıtlı çalışanların adlarını ve telefon numaralarını barındıran bir liste gösterecektir. Buradan bir çalışan seçilmesi durumunda çalışana ait detay bilgi gösterimi yapılacaktır.
• AdminUI için gerek şifre değiştirilebilir olacaktır.
• AdminUI arayüzünden yeni çalışan girişi yapılabilecektir.
• Çalışanın ad, soyad ve telefon bilgisinin girilmesi zorunludur.
• Departman bilgisi, veritabanından alınarak dropdownlist’ten seçtirilecektir.
• Yönetici bilgisi, dropdownlist’ten seçtirilecektir. Bu dropdownlist sistemde mevcut bulunan çalışan kayıtları üzerinden doldurulacaktır.
• Çalışan kayıtları AdminUI üzerinden düzenlenebilecek ve silinebilecektir. Kural olarak eğer ilgili çalışan başka bir çalışanın yöneticisi statüsünde bulunuyor ise silme işlemine izin verilmeyecektir.
• Sistemde kayıtlı bulanan departmanlar yönetilebilir olacaktır. Ekleme, Düzenleme ve Silme işlemlerine izin verilecektir. Kural olarak ilgili departmanın altında tanımlı çalışan varsa departman silinemeyecektir.

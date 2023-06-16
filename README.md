# configstealer
Konfigürasyon dosyası kopyalayıcı :))))

Aşağıda, bir PHP script içerisinde başka bir PHP dosyasını kopyalayarak yeni bir dosya oluşturmanızı sağlayacak bir örnek kod bulunmaktadır:

```php
<?php
$sourceFile = 'config.php';  // Kopyalanacak olan dosyanın adı ve yolunu buraya girin
$destinationFile = 'config.txt';  // Oluşturulacak yeni dosyanın adını ve yolunu buraya girin

// Dosyayı kopyalama işlemi
if (copy($sourceFile, $destinationFile)) {
    echo 'Dosya kopyalandı ve yeni dosya oluşturuldu: ' . $destinationFile;
} else {
    echo 'Dosya kopyalama işleminde bir hata oluştu.';
}
?>
```

Yukarıdaki kodu kullanarak, `config.php` dosyasını `config.txt` olarak aynı sunucuya kopyalayabilirsiniz. Kopyalama işlemi başarılı olduğunda, "Dosya kopyalandı ve yeni dosya oluşturuldu: config.txt" mesajını göreceksiniz. Eğer bir hata oluşursa, "Dosya kopyalama işleminde bir hata oluştu." mesajını alacaksınız.

Kodun çalışabilmesi için, PHP scriptinizi çalıştırdığınız dizinde veya belirttiğiniz dosya yollarında, kopyalayacağınız `config.php` dosyasının bulunması gerekmektedir. Ayrıca, PHP'nin dosyaları kopyalama izni olduğundan emin olmalısınız.

Bu kod parçasını kullanarak, `config.php` dosyasını `config.txt` olarak kopyalayabilir ve yeni bir dosya oluşturabilirsiniz.

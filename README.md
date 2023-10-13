<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Harcama Hesaplayıcı</h1>
    <h2>Yapılacaklar</h2>
    <ul>
        <li><strong>Ekleme Özelliği:</strong>
            <ol>
                <li>Ekle butonuna tıklanıldığında inputların verilerine erişin.</li>
                <li>Eğer inputlar boşsa, kullanıcıya bir uyarı verin.</li>
                <li>Inputlar boş değilse, bir harcama kartını ekrana ekleyin.</li>
                <li>Harcama kartının "Ödendi" kutusu işaretlendiğinde, bu elemana "paid" sınıfını ekleyin.</li>
                <li>Tüm inputları temizleyin.</li>
            </ol>
        </li><li><strong>Toplam Bilgisi:</strong>
            <ol>
                <li>HTML'de bir toplam alanı oluşturun ve JavaScript'te bir "toplam" değişkeni oluşturun.</li>
                <li>Her harcama eklediğinizde, harcamanın fiyatını "toplam" değişkenine ekleyin.</li>
                <li>Bir harcama silindiğinde, bu fiyatı "toplam"dan çıkarın.</li>
                <li>Her "toplam" değiştiğinde, ekrandaki toplam bilgisini güncelleyin.</li>
            </ol>
        </li>
        <li><strong>Silme | Güncelleme Özelliği:</strong>
            <ol>
                <li>Listedeki tüm tıklanma olaylarını izleyin.</li>
                <li>Tıklanan elemanın ID'si "delete" ise, bu elemanı kaldırın ve toplamdan fiyatı çıkarın.</li>
                <li>Tıklanan elemanın ID'si "update" ise, "paid" sınıfını ekleyin veya çıkarın.</li>
            </ol>
        </li>
        <li><strong>Harcamaları Filtreleme:</strong>
            <ol>
                <li>HTML'de bir seçim alanı (select) oluşturun.</li>
                <li>Select alanındaki değer değiştikçe, seçilen bilgiyi alın.</li>
                <li>Seçilen değere göre harcamaları filtreleyin.</li>
            </ol>
        </li>
    </ul>
    <h2>Kullanım</h2>
    <ol>
        <li>Projeyi tarayıcınızda veya bir web sunucusunda açın.</li>
        <li>Harcama eklemek için "Ekle" butonuna tıklayın.</li>
        <li>Gerekli bilgileri girin ve "Ödendi" kutusunu işaretleyin veya temizleyin.</li>
        <li>Harcama ekledikten sonra toplam tutarı ekranda görebilirsiniz.</li>
        <li>Harcamaları silmek veya güncellemek için ilgili düğmelere tıklayın.</li>
        <li>Harcamaları seçilen kriterlere göre filtrelemek için filtre seçimini kullanın.</li>
    </ol>
</body>
</html>

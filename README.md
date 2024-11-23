# Müşteri Finansal Verilerinin Analizi ve Görselleştirilmesi

Bu proje, müşteri finansal bilgilerini içeren geniş bir veri setinin analizi için geliştirilmiştir. Proje, finansal verilerin keşfi, analizi, modelleme için hazırlanması ve görselleştirilmesini içermektedir. Özellikle kredi risk analizi, müşteri segmentasyonu ve finansal davranış modellemesi gibi alanlarda kullanılabilir.

## Veri Seti Hakkında

### Genel Bilgiler
- **Satır Sayısı**: 100.000
- **Sütun Sayısı**: 27
- **Veri Formatı**: CSV
- **Dosya Boyutu**: ~10.3 MB (hafıza kullanımı)
- **Eksik Veri**: Bazı sütunlarda eksik değerler bulunmaktadır (örneğin, `Name`, `Monthly_Inhand_Salary` ve `Type_of_Loan`).

### Veri Seti Yapısı
Veri seti, müşterilere ait finansal profilleri detaylı bir şekilde analiz etmek amacıyla düzenlenmiştir. Her bir satır bir müşteri kaydını temsil eder ve her sütun bir özelliği ifade eder. Örnek sütunlar ve açıklamaları:

- **ID**: Her kayda atanmış benzersiz bir kimlik.
- **Customer_ID**: Her müşteriye ait benzersiz kimlik.
- **Month**: Verinin ait olduğu ay.
- **Name**: Müşterinin adı (eksik değerler mevcut).
- **Age**: Müşteri yaşı.
- **Occupation**: Müşterinin mesleği.
- **Annual_Income**: Yıllık gelir.
- **Monthly_Inhand_Salary**: Aylık elde edilen gelir (eksik değerler var).
- **Num_Bank_Accounts**: Banka hesaplarının toplam sayısı.
- **Num_Credit_Card**: Kredi kartı sayısı.
- **Interest_Rate**: Uygulanan faiz oranı.
- **Outstanding_Debt**: Ödenmemiş borç miktarı.
- **Credit_Utilization_Ratio**: Kredi kullanım oranı.
- **Payment_Behaviour**: Ödeme davranışı (örneğin, düşük harcama, yüksek ödeme gibi).

### Eksik Veriler
Bazı sütunlarda eksik veri bulunmaktadır. Eksik veri oranları:
- **Name**: %10 eksik.
- **Monthly_Inhand_Salary**: %15 eksik.
- **Type_of_Loan**: %11 eksik.

Eksik veriler, analiz ve modelleme sürecinde özel yöntemlerle ele alınabilir (örneğin, ortalama doldurma, regresyon tahmini veya çıkarma).

## Projenin Amacı

Bu veri setiyle yapılabilecek analiz ve çalışmalar:
1. **Finansal Risk Analizi**:
   - Müşterilerin kredi borçlanma alışkanlıklarını inceleyerek kredi riski tahmini yapılabilir.
2. **Müşteri Segmentasyonu**:
   - Farklı müşteri gruplarını belirlemek için sınıflandırma algoritmaları kullanılabilir.
3. **Kredi Kullanımı ve Gelir Analizi**:
   - Kredi kullanım oranları ve gelir seviyelerinin ilişkisini analiz ederek, müşteri profilleri hakkında çıkarımlar yapılabilir.
4. **Veri Görselleştirme**:
   - Müşteri davranışlarının anlaşılmasını kolaylaştırmak için grafikler ve raporlar oluşturulabilir.

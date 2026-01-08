# Dart Örnekleri

Bu proje, Dart programlama dili ile geliştirilmiş çeşitli örnek uygulamaları içermektedir. Her dosya, Dart'ın farklı özelliklerini ve programlama konseptlerini öğrenmek için tasarlanmıştır.

## Proje Yapısı

```text
mobile_programing/
├── README.md
├── hello.dart          # Temel başlangıç örneği
├── calculator.dart     # Hesap makinesi uygulaması
├── quiz.dart           # Quiz uygulaması
├── animal.dart         # Kalıtım (inheritance) örneği
├── bottle.dart         # Interface ve Factory Pattern
├── camera.dart         # Getter/Setter örneği
├── house.dart          # Liste işlemleri
├── laptop.dart         # Sınıf metodları
├── list.dart           # Asenkron programlama
├── random.dart         # Rastgele sayı ve Null Safety
├── gender.dart         # Enum kullanımı
└── second.dart         # Asenkron gecikme örneği
```

## Kullanım

Her dosyayı ayrı ayrı çalıştırabilirsiniz:

```bash
dart run hello.dart
dart run calculator.dart
dart run quiz.dart
# ... diğer dosyalar için de aynı şekilde
```

## Öğrenilen Konseptler

### 1. **hello.dart** - Temel Başlangıç

- Basit `print` kullanımı
- `main()` fonksiyonu

### 2. **calculator.dart** - Hesap Makinesi

- Fonksiyon tanımlama
- Named parameters (`required`, optional)
- Konsol girişi (`stdin.readLineSync()`)
- Switch-case yapısı
- While döngüsü
- Hata yönetimi (sıfıra bölme kontrolü)

### 3. **quiz.dart** - Quiz Uygulaması

- Sınıf tanımlama (`class`)
- Nesne yönelimli programlama (OOP)
- Liste kullanımı (`List`)
- Metodlar ve özellikler
- Puanlama sistemi

### 4. **animal.dart** - Kalıtım (Inheritance)

- Base class (`Hayvan`)
- Türetilmiş sınıf (`Kedi extends Hayvan`)
- `super` anahtar kelimesi
- Constructor'lar

### 5. **bottle.dart** - Interface ve Factory Pattern

- Abstract class tanımlama
- Interface implementasyonu (`implements`)
- Factory pattern
- `@override` annotation

### 6. **camera.dart** - Getter/Setter

- Getter metodları
- Setter metodları
- Encapsulation (kapsülleme)

### 7. **house.dart** - Liste İşlemleri

- Nesne listesi oluşturma
- For-in döngüsü
- Liste içinde nesne işleme

### 8. **laptop.dart** - Sınıf Metodları

- Sınıf içinde metod tanımlama
- Nesne metodlarını çağırma

### 9. **list.dart** - Asenkron Programlama

- `Future` kullanımı
- `async`/`await` anahtar kelimeleri
- `Future.wait()` ile paralel işlemler
- `Future.delayed()` ile gecikme

### 10. **random.dart** - Rastgele Sayı ve Null Safety

- `Random` sınıfı
- Null safety (`int?`)
- Null-coalescing operatörü (`??`)
- Koşullu ifadeler

### 11. **gender.dart** - Enum Kullanımı

- Enum tanımlama
- Enum değerlerine erişim (`values`)

### 12. **second.dart** - Asenkron Gecikme

- Kullanıcı girişi alma
- Asenkron gecikme (`Future.delayed`)
- Geri sayım animasyonu

## Öğrenilen Dart Özellikleri

- ✅ **Sınıflar ve Nesneler**: OOP temelleri
- ✅ **Kalıtım (Inheritance)**: `extends` kullanımı
- ✅ **Abstract Class**: Interface benzeri kullanım
- ✅ **Getter/Setter**: Özellik erişimi ve değiştirme
- ✅ **Enum**: Sabit değer listeleri
- ✅ **Asenkron Programlama**: `async`/`await`, `Future`
- ✅ **Null Safety**: Nullable tipler ve güvenli null işleme
- ✅ **Liste İşlemleri**: `List` kullanımı ve döngüler
- ✅ **Konsol I/O**: Kullanıcı girişi ve çıktısı
- ✅ **Fonksiyonlar**: Named parameters, optional parameters
- ✅ **Kontrol Yapıları**: if-else, switch-case, döngüler

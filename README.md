# Çay ve Kahve Tüketimine Göre Uyku Tahmini

## Proje Hakkında

Bu projede günlük çay ve kahve tüketimi ile uyku süresi arasındaki ilişki incelenmiştir. Python ve makine öğrenmesi yöntemleri kullanılarak girilen tüketim miktarlarına göre uyku süresi tahmini yapan bir uygulama geliştirilmiştir.

## Projenin Amacı

Projenin amacı, Python ile veri analizi ve makine öğrenmesi süreçlerini uygulamalı olarak gerçekleştirmektir. Veri oluşturma, temizleme, görselleştirme, model eğitimi ve değerlendirme aşamaları Google Colab ortamında tamamlanmıştır.

## Kullanılan Teknolojiler

- Python
- Google Colab
- Pandas ve NumPy
- Matplotlib
- Scikit-learn
- Gradio

## Veri Seti

Çalışmada 300 satırdan oluşan yapay bir veri seti kullanılmıştır. Veri seti günlük çay tüketimi, kahve tüketimi ve uyku süresi değişkenlerini içermektedir.

Veri temizleme aşamasında eksik ve tekrarlanan kayıtlar kontrol edilmiş, temizleme sonrasında 296 kayıt ile çalışılmıştır.

## Model Geliştirme

Uyku süresini tahmin etmek için Linear Regression algoritması tercih edilmiştir. Veri setinin %80'i eğitim, %20'si test amacıyla ayrılmıştır.

Modelin performansı MAE, MSE, RMSE ve R² metrikleriyle değerlendirilmiştir.

## Uygulama

Gradio kullanılarak basit bir kullanıcı arayüzü geliştirilmiştir. Kullanıcılar günlük çay ve kahve tüketim mikt

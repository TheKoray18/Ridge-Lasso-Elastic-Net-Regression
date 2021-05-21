# Ridge-Lasso-Elastic-Net-Regression

# Ridge Regression 

- Amacımız hata kareler toplamını minimize eden katsayıları bu katsayılara bir ceza uygulayarak bulmaktır.
- Ridge Regresyon ; Tüm değişkenler ile model kurar.İlgisiz değişkenleri modelden çıkarmaz,katsayıları sıfıra yaklaştırır.
- **Overfitting**'e karşı dirençlidir.
- **lambda(alpha)** için iyi bir değer bulunması önemlidir.Bunun için CV yöntemi kullanılır.

# Lasso Regression 

- Amacımız hata kareler toplamını minimize eden katsayıları bu katsayılara bir ceza uygulayarak bulmaktır
- Lasso'da katsayılar sıfıra yaklaştırılı.Fakat **L1** normu **lambda** yeteri kadar büyük olduğunda bazı katsayıları sıfır yapar.Böylece değişken seçimi yapmış oluruz.
- **lambda**'nın doğru seçilmesi çok önemlidir.Burada da cv kullanılır.
- **Ridge** ve **Lasso** yöntemi birbirinden üstün değildir.

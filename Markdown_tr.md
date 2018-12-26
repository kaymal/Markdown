# Markdown Temelleleri 

## Markdown Nedir, Ne Amaçla Kullanılır?

Markdown, yazılarımızı düz metin olarak yazmamıza imkan veren işaretleme/biçimlendirme dilidir (_markup language_).  Markdown'ın temel amacı, metnimizi kolayca hazırlamak ve düz metin haliyle bile metnin rahatça okunmasını sağlamaktır. 

## Örneklerle Sözdizim (_syntax_) kuralları

[Başlık](#Başlık)

[Vurgulama](#Vurgulama)

[Maddeleme, Sıralama](#Maddeleme)

[Bağlantı](#Bağlantı)

[Tablo](#Tablo)

[Resim](#Resim)


### Başlık

```
# Başlık
## Alt Başlık
```

# Başlık
## Alt Başlık


### Vurgulama

```
**kalın** __kalın__ deneme

*italik* _italik_

**_kalın ve italik_**
```

**kalın** __kalın__

*italik* _italik_

**_kalın ve italik_**

### Maddeleme, Sıralama

*Maddeleme:*

```
- Maddde 1
- Madde 2
- Madde 3
  * Alt madde a
  * Alt madde b
    - Fıkra i
    - Fıkra ii
```
- Maddde 1
- Madde 2
- Madde 3
  * Alt madde a
  * Alt madde b
    - Fıkra i
    - Fıkra ii

*Sıralama:*

```
1. Birinci
2. İkinci
```
1. Birinci
2. İkinci


### Bağlantı

````
[Bağlantı](https://github.com/kaymal)

[Başlıklı Bağlantı](https://github.com/kaymal "GitHub Sayfam")
````

[Bağlantı](https://github.com/kaymal)

[Başlıklı Bağlantı](https://github.com/kaymal "GitHub Sayfam")


```
[Referans 1][1]
[Referans 2][2]

xxxxxxxxxxxxxx

[1]: https://github.com/kaymal
[2]: https://github.com/
```

[Bağlantı 1][1]

[Bağlantı 2][2]

xxxxxxxxxxxxxxx

[1]: https://github.com/kaymal
[2]: https://github.com/



### Tablo

|   | Fiyat   | Adet  |
| --|:-------:| -----:|
| A | 1000TL  | 1     |
| B | 100TL   | 10    |
| C | 1TL     | 1000  |


### Resim/Görsel
```
Resim: 
![alt yazı][resim]

[resim]: https://www.freeiconspng.com/uploads/github-logo-icon-0.png"Resim Başlığı"
```


Resim: 
![alt yazı][resim]

[resim]: https://www.freeiconspng.com/uploads/github-logo-icon-0.png "Resim Başlığı"

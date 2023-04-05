---
title: 'Data Tipleri'
---

## URL

Sistemde bulunan kullanıcı ilişkili  tiplerin listelerini  sorgulamak için kullanılan endpoint ve http metod bilgisi aşağıda verilmiştir.


| HTTP Method                        | URL                         |
| --------------------------| --------------------------- |
| <span style="background-color: #f9f2f4; color: #9c1d3d">GET</span> | /tanimlar/v1/data-tipleri |



## Dönüş Parametreleri

| Parametre                        | Tip                         | Açıklama |
| :--------------------------: | :---------------------------: | :-------------------: | :-------------------: |
| <span style="background-color: #f9f2f4; color: #9c1d3d">code</span>  | <span style="background-color: #f9f2f4; color: #9c1d3d">string</span>   | Kod |
| <span style="background-color: #f9f2f4; color: #9c1d3d">name</span>  | <span style="background-color: #f9f2f4; color: #9c1d3d">string</span>   | İsim |
| <span style="background-color: #f9f2f4; color: #9c1d3d">description</span>  | <span style="background-color: #f9f2f4; color: #9c1d3d">string</span>   | Açıklama |
| <span style="background-color: #f9f2f4; color: #9c1d3d">items</span>  | <span style="background-color: #f9f2f4; color: #9c1d3d">obje</span>   | Öğeler |
| <span style="background-color: #f9f2f4; color: #9c1d3d">key</span>  | <span style="background-color: #f9f2f4; color: #9c1d3d">string</span>   | Şifre |
| <span style="background-color: #f9f2f4; color: #9c1d3d">text</span>  | <span style="background-color: #f9f2f4; color: #9c1d3d">string</span>   | Metin |
| <span style="background-color: #f9f2f4; color: #9c1d3d">description</span>  | <span style="background-color: #f9f2f4; color: #9c1d3d">string</span>   | Açıklama (items) |



**İSTEK** _(GET):_
``` markup

Boş JSON gönderilir

```

**YANIT:**
``` markup

        "code": "TR.SP.DataCode.KullaniciTur",
        "name": null,
        "description": "API Kullanıcı Turu",
        "items": [
            {
                "key": "hhh",
                "text": "Hesap Hizmeti",
                "description": "Hesap Hizmeti"
            },
        ]
```

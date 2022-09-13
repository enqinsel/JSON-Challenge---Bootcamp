# JSON-Challenge---Bootcamp
I processed the data from the JSON file in the desired template.

#Projenin Ekran Görüntüsü;
---
[DEMO LIVE](https://json-challenge-bootcamp-patika.netlify.app/)
![Ek Açıklama 2022-09-13 202713](https://user-images.githubusercontent.com/76450122/189971223-6ef91f88-7974-42bf-830c-35ea8095e3b7.jpg)


# Template

Bize paylaşılan [JSON](https://github.com/Front-End-Bootcamp/vue-bootcamp/blob/d6f881aec77f15a4107eafc10f6a91e90f9268a4/homework%201/data.json) dosyasında bulunan kişileri ve asistanları gruplamamız istendi. 

Aşağıdaki gibi bulunan JSON dosyasının;
```
	{
		"name": "",
		"id": "",
		"group": "SteelBlue",
		"type": null
	},
	{
		"name": "",
		"id": "",
		"group": "SteelBlue",
		"type": "assistant"
	}
```

Aşağıda belirtilen şeklinde veya benzer yapıda düzenlenmesi gerekiyor

```
	{
		"group": "SteelBlue",
		"student": [name, name]
		"assistant": "name"
	},
```

veya

```
	{
		"SteelBlue": {
			"student": [name, name]
			"assistant": "name"
		}
	}
```

Çalışma sonunda belirlenen fonsiyonlar çağırıldığında JSON verisinin düzenlenmiş haliyle çıktısının alınması gerekiyor.

Örneğin: ```getGroup("SteelBlue")``` fonsiyonu çağrıldığında çıktısının yukarıda belirtilen sonuçlardan birinin veya benzerinin olması gerekiyor.

Kullanılabilecek bazı fonsiyon isim önerileri;
```filterByGroupName()```
```getGroupStudents```

Ek olarak ```getGroups``` fonksiyonu ile tüm JSON düzenlenmiş haliyle console da görüntülenebilinir.

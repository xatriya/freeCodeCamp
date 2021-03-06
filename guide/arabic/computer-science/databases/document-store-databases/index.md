---
title: Document Store Databases
localeTitle: قواعد بيانات مخزن المستندات
---
## قواعد بيانات مخزن المستندات

تعتبر قاعدة بيانات مخزن المستندات هي نوع آخر من قاعدة بيانات NoSQL التي تشبه إلى حد كبير قاعدة بيانات Key Value. يمثل السجل في مخزن المستندات وثيقة منظمة واحدة يمكن أن تكون مختلفة عن كل الوثائق الأخرى في قاعدة البيانات. بخلاف قاعدة بيانات علائقية ، لا يوجد تعيين كائنات إلى جدول مختلف في قاعدة البيانات. بدلاً من ذلك ، يمكننا أخذ الكائن بأكمله وكتابته مباشرةً في قاعدة بيانات مخزن المستندات.

على سبيل المثال ، يمكن أن يكون لدينا الكائن التالي داخل الكود الخاص بنا.

```json
{
    "name": "freeCodeCamp",
    "job": "contributor"
}
``` 

يمكن كتابة هذا الكائن بأكمله مباشرة في قاعدة بيانات مخزن المستندات بدون تحليل إضافي.

#### معلومات اكثر:

[MongoDB](https://www.mongodb.com/document-databases)

[Elasticsearch](https://www.elastic.co/)
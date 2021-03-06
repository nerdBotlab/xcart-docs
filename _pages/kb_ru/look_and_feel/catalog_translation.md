---
lang: ru
layout: article_with_sidebar
updated_at: '2018-06-04 22:53 +0400'
identifier: ref_7bXXWi0F
title: Изменение языка каталога товаров
order: 300
published: true
---
Тексты страниц магазина хранятся в языковых метках. Для перевода каталога магазина на другой язык создайте копии языковых меток каталога на другом языке и переведите их значения на новый язык. Потребуется перевод категорий, названий товаров, описаний и т.д. Простой способ - экспортировать информацию о категориях и товарах в CSV файл, сделать перевод на новый язык в этом файле и экспортировать информацию обратно в магазин. 

{% note info %}
Чтобы перевести каталог на новый язык, предварительно {% link "установите модуль перевода" ref_translation %} на этот язык.
{% endnote %}

1. Экспорт каталога товаров
  
   В разделе **Каталог / Экспорт** выберите данные для экспорта и нажмите **Начать экспорт**.

   ![2.jpg]({{site.baseurl}}/attachments/ref_7bXXWi0F/2.jpg)
  
   Будет создан СSV файл с выбранной информацией на стандартном языке магазина.

2. Перевод каталога товаров на другой язык
  
   Откройте скачанный CSV файл в редактрое (MS Excel, LibreOffice Calc, Google Таблицы) и перевдите информации о категориях и товарах. Рядом с каждым столбцом создайте новый столбец с тем же названием, но на языке перевода. В новом столбце сделайте перевод соответствующих языковых меток. Получится файл следующего вида:

   ![3.jpg]({{site.baseurl}}/attachments/ref_7bXXWi0F/3.jpg)

   Когда перевод завершён, столбцы на языке оригинала можно удалить. В файле должен остаться столбец SKU и все остальные столбцы на языке перевода. {% link "Импортируйте" ref_AwaMbiEf %}  файл обратно в магазин.

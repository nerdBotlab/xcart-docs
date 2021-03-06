---
lang: ru
layout: article_with_sidebar
updated_at: '2017-11-09 14:50 +0400'
identifier: ref_REno3u9g
title: Создание товаров в X-Cart
order: 10
published: true
---
Данная статья рассказывает, как создать товары в магазине вручную. Кроме того, товары можно внести в магазин путем {% link "импорта" ref_94dTTrT5 %}. 

## Создание нового товара

1.  В панели управления магазина откройте страницу **"Каталог / Товары"** 
    ![1.jpg]({{site.baseurl}}/attachments/ref_REno3u9g/1.jpg)
    
2.  Нажмите кнопку **"Добавить товар"**
    ![2.jpg]({{site.baseurl}}/attachments/ref_REno3u9g/2.jpg)
    
    Откроется страница создания товара 
    
    ![3.jpg]({{site.baseurl}}/attachments/ref_REno3u9g/3.jpg)
    
3.  Заполните поля информацией о новом товаре. **Название**  - единственное обязательное поле.  

4.  Нажмите кнопку **"Добавить товар"** 

    ![5.jpg]({{site.baseurl}}/attachments/ref_REno3u9g/5.jpg)

товар готов.

## Информация о товаре

Создавая новый товар, вы можете указать следующие данные:

*   **Название товара** - название, по которому вы и ваши покупатели будут находить товар в магазине.
*   **Артикул** - уникальный номер товара.
*   **Изображения** - фотографии товара.
*   **Категория** - одна или несколько категорий, в которые будет входить товар.
*   **Описание** - краткое описание товара, отображаемое на страницах со списками товаров.
*   **Полное описание** - подробное описание товара, доступное на странице товара.
*   **Разрешить покупателям прикреплять файлы к этому товару**.
*   **Теги**.
*   **Доступен для продажи** - эта опция отвечает за доступность товара в магазине. Если ее отключить, покупатели не найдут товар в магазине.  
*   **Группы пользователей** - пользователи, которые смогут купить данный товар. Незарегистрированные покупатели или члены не указанных здесь групп не увидят товар в магазина.
*   **Класс налога** - класс налогов, к которому принадлежит товар (определяет, какие налоги применимы к товару). В этой {% link "статье" ref_CqF1z2kG %} вы найдете Информацию о классах налогов. 
*   **Цена** - стоимость товара.
*   **Рыночная цена** - укажите среднюю стоимость этого товара на рынке. Покупатель увидит разницу между стоимостью товара на рынке и в вашем магазине, выгода указана в процентах. Опция доступна после активации бесплатного модуля [Рыночная цена (Market price)](https://market.x-cart.com/addons/market-price.html "Создание товаров в X-Cart").
*   **Распродажа** - эта опция помещает товар на распродажу.
*   **Дата поступления** - дата, когда началась продажа товара в магазине. Это поле носит лишь информативный характер, хотя информация может быть полезна некоторым модулям (например, модулю, который позволяет создать товар в каталоге заранее и автоматически сделать его доступным покупателям, когда наступит указанная дата его поступления).
*   **Контроль остатков** (включен / отключен) - с помощью этого переключателя можно включить или отключить отслеживание количества товара в наличии. Если запас товара не ограничен, эту опцию можно отключить.
*   **Остаток** - точное текущее количество штук данного товара в наличии.
*   **Вес** - вес товара.
*   **Требуется доставка** - эта опция показывает, доставляется данный товар или нет.
*   **Бесплатная доставка** - эта опция делает доставку товара бесплатной.
*   **Фиксированная стоимость доставки**.
*   **Отправка отдельной посылкой** - эта опция показывает, что товар нужно отправлять отдельно от других товаров в ордере. Для отправки в отдельной коробке можно указать размеры коробки и количество помещаемых в нее товаров. 
*   **Мета тэги Open Graph** - мета тэги, позволяющие поделиться ссылкой на товар в Facebook.
*   **Мета описание** - ключевые слова, которые используются в мета тэге description на странице товара (для SEO).
*   **Мета ключевые слова** - ключевые слова, которые используются в мета тэге keywords на странице товара (для SEO).
*   **Заголовок страницы товара** - заголовок страницы о товаре, необходим для SEO.
*   **ЧПУ** - семантическая ссылка на товар (для SEO).


## Отслеживание изменения количества товара

1.  Откройте страницу товара, для которого нужно настроить отслеживание количества. 

2.  Перейдите на вкладку **"Контроль остатков"**:

    ![6.jpg]({{site.baseurl}}/attachments/ref_REno3u9g/6.jpg)
    
    На страницу управления количеством товара можно, также, перейти по ссылке **"Контроль
   остатков"** в разделе **"Цены и наличие на складе"** в информации о товаре:
   
    ![7.jpg]({{site.baseurl}}/attachments/ref_REno3u9g/7.jpg)
    
    Открывается страница настроек:
    
    ![8.jpg]({{site.baseurl}}/attachments/ref_REno3u9g/8.jpg)
    
3.  Настройка отслеживание количества товара:

    *   **Дата поступления** - дата, когда началась продажа товара в магазине.
    *   **Контроль остатков (включен / отключен)** - с помощью этого переключателя можно _включить_ или _отключить_ отслеживание количества товара в наличии. Если запас товара не ограничен, эту опцию можно _отключить_.
    *   **Остаток** - точное текущее количество штук данного товара в наличии.
    *   **Отображать предупреждение о низком остатке товара на странице товара** - данная опция активирует предупреждение для покупателей, что данного товара осталось мало. 
    *   **Уведомлять администратора при уменьшении остатка данного товара на складе до определенного предела** (включено / отключено) - если опция _включена_, администратор магазина получает уведомление о снижении количества товара. Данная опция требует заполнения следующего поля ("Минимальное количество"), в котором устанавливается количество товара, при котором администратор получает предупреждение. Если опция _отключена_, администратор не получает сообщений о том, что товар заканчивается.  
    *   **Минимально количество** - в этом поле указывается количество товара, которое считается низким. При включенной опции выше, администратор получает предупреждение, когда количество товара достигает этого значения. 
4.  Нажмите **"Сохранить"**.

## Дополнительные параметры товара (цвет, материал, страна-производитель и т.д.)

Такую информацию можно добавить как свойства товара на вкладке **"Атрибуты"**.

![9.jpg]({{site.baseurl}}/attachments/ref_REno3u9g/9.jpg)

Покупатели увидят эти атрибуты в разделе **"Характеристики"** на странице товара.

Атрибуты товаров подробно описаны в статье {% link "Классы и атрибуты товаров" ref_pXBwGdtu %}.

## Варианты товаров (цвет, размер и т.д.)

В X-Cart 5 варианты товаров настраиваются на основе атрибутов. Задайте атрибут "Размер" и несколько значений для него - "XS", "S", "M". Так, покупатель сможет выбрать один из вариантов размера. Примеры создания вариантов на основе атрибутов описаны в статье {% link "Работа со значениями атрибутов" ref_SuWz9rmN %}. Более подробная информация об атрибутах товаров - {% link "Классы и атрибуты товаров" ref_pXBwGdtu %}.

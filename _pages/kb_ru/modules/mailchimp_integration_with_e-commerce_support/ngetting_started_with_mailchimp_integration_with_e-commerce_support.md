---
lang: ru
layout: article_with_sidebar
updated_at: '2018-06-15 17:29 +0400'
title: Установка модуля и подключение к сервису рассылок MailChimp
order: 100
published: true
identifier: ref_5M7eFcuG
---
## Установка модуля 

[MailChimp](https://market.x-cart.com/addons/mailchimp-integration-with-e-commerce.html "Установка модуля и подключение к сервису рассылок MailChimp") - бесплатный модуль. Он установлен и активирован по умолчанию. Найдите модуль и ссылку на его настройки в разделе **Мои модули**.

Чтобы подключить магазин к сервису **MailChimp**, активируйте модуль.

Для настройки рассылок понадобится и стандартный модуль рассылок **Newsletter subscriptions**.

![7.jpg]({{site.baseurl}}/attachments/ref_6sRMggED/7.jpg)

Модуль **Newsletter subscriptions** отвечает за блок **Подписаться на новости**, где покупатели подписываются на новостную рассылку магазина.

Если активирован только модуль **Newsletter subscriptions**, адреса, введённые в этой форме, вносятся в списки подписчиков в разделе **Каналы продаж / Рассылка** в панели управления магазина.

<div class="ui stackable two column grid">
  <div class="column" markdown="span">![3.jpg]({{site.baseurl}}/attachments/ref_6sRMggED/3.jpg)

</div>
  <div class="column" markdown="span">![4.jpg]({{site.baseurl}}/attachments/ref_6sRMggED/4.jpg)
</div>
</div>

Если активирован и модуль **MailChimp**, списки подписчиков больше не сохраняются в панели управления магазина. Управление списками и группами подписчиков происходит в учётной записи **MailChimp**.

Если на момент подключения к **MailChimp** в магазине уже существовал список подписчиков, сформированный модулем **Newsletter subscriptions**, он не будет автоматически перенесён в **MailChimp**. Экспортируйте готовые списки из магазина и [импортируйте в MailChimp](https://mailchimp.com/help/import-subscribers-to-a-list/ "Установка модуля и подключение к сервису рассылок MailChimp"). 

![5.jpg]({{site.baseurl}}/attachments/ref_6sRMggED/5.jpg)

## Подключение магазина к сервису MailChimp

### Регистрация в **MailChimp**

Для подключения магазина к сервису **MailChimp** откройте настройки модуля по ссылке в разделе магазина **Мои модули** и учётную запись **MailChimp** на соседних вкладках браузера. Так выгладит страница настроек модуля до подключения к сервису

![6.jpg]({{site.baseurl}}/attachments/ref_6sRMggED/6.jpg)

Если у вас уже есть учётная запись **MailChimp**, переходите к настройкам ниже, если нет - [зарегистрируйтесь](https://login.mailchimp.com/signup/ "Установка модуля и подключение к сервису рассылок MailChimp"). 

### Подключение магазина к **MailChimp**

- В учётной записи **MailChimp** настройте [API ключ](https://mailchimp.com/help/about-api-keys/ "Установка модуля и подключение к сервису рассылок MailChimp"), необходимый для связи с X-Cart.

![10.jpg]({{site.baseurl}}/attachments/Установка модуля и подключение к сервису рассылок MailChimp/10.jpg)

- 1 способ:
В настройках модуля в магазине нажмите **Подключить аккаунт MailChimp** и войдите в  [учётную запись MailChimp](https://login.mailchimp.com/ "Установка модуля и подключение к сервису рассылок MailChimp").  

- 2 способ:
Войдите в учётную запись **MailChimp** и скопируйте созданный для магазина [API кллюч](https://mailchimp.com/help/about-api-keys/ "Установка модуля и подключение к сервису рассылок MailChimp"). Внесите этот ключ в настройки модуля.

![11.jpg]({{site.baseurl}}/attachments/Установка модуля и подключение к сервису рассылок MailChimp/11.jpg)

После подключения магазина к **MailChimp** по ссылке **Настройки** открывается страница параметров модуля.

![12.jpg]({{site.baseurl}}/attachments/Установка модуля и подключение к сервису рассылок MailChimp/12.jpg)

### Списки подписчиков

Если до подключения к X-Cart в **MailChimp** были созданы списки, они автоматически импортируются в магазин после подключения. Найдите и активируйте нужные списки в разделе **Каналы продаж / MailChimp lists**. Дополнительная информация о списках в X-Cart и в [MailChimp](https://mailchimp.com/help/lists/ "Установка модуля и подключение к сервису рассылок MailChimp"). 

Покупатели могут подписаться на рассылку на странице регистрации в магазине и оплаты покупки. Зарегистрированные покупатели могут подписаться на дополнительные рассылки или отказаться от рассылок в настройках учётной записи. Администратор также может изменять подписки покупателей в настройках учётных записей покупателей в панели управления. 

### Создание рассылок

Настроенные [рассылки](https://mailchimp.com/help/emails/ "Установка модуля и подключение к сервису рассылок MailChimp") можно использовать для проведения акций, которые настраиваются в панели управления **MailChimp**.

Чтобы видеть продажи по результатам акции, настройте отслеживание переходов по ссылкам из рассылки:

   1.  На странице **Campaigns** в панели управления **MailChimp** нажмите на название акции. Внизу страницы нажмите **Edit** рядом с названием секции **Settings & Tracking**.
   2.  Отметьте опцию  **E-commerce link tracking** и нажмите **Save**. 
   
С помощью этой настройки вы получите список покупателей, привлечённых в магазин рассылкой, отследите их покупательскую активность и передадите эту информацию в **MailChimp**. В разделе **Reports** панели управления **MailChimp** появится информация о заказах, конверсии и объёму продаж. 

![8.jpg]({{site.baseurl}}/attachments/ref_6sRMggED/8.jpg)

**MailChimp** классифицирует получателей рассылок по покупательской активности: по сумме заказа, частоте заказов, предпочтению товаров. **MailChimp** определяет, рассылки о каких товарах отправлять тем или иным подписчикам.

**MailChimp** делает автоматические рассылки или серии писем по каждому действию покупателя в магазине - регистрация, подписка на новости, забытая корзина, первая покупка, выбор товара, выбор категории и т.п.

## Отключение от сервиса **MailChimp**

Отключение от сервиса **MailChimp** осуществляется для того, чтобы подключить магазин к другой учётной записи **MailChimp** или подключить магазин к той же учётной записи **MailChimp** с новым API ключом:

   1. Зарегистрируйте новую учётную запись **MailChimp** и создайте в ней [API кллюч](https://mailchimp.com/help/about-api-keys/ "Установка модуля и подключение к сервису рассылок MailChimp") для вязи с магазином.

   2. В настройках модуля в магазине нажмите **Переподключить аккаунт MailChimp**. 
   
   3. Введите логин и пароль новой учётной записи **MailChimp**, к который подключаете магазин.

   Магазин отключён от предыдущего и подключён к новому логину **MailChimp**.


### Отключение и удаление модуля

Чтобы полностью остановить работу **MailChimp**, отключите модуль **MailChimp** в разделе **Мои модули** в магазине. Рассылки через **MailChimp** перестанут работать, но настройки модуля и накопленная во время работы модуля информация сохранятся. Полное удаление всей информации возможно только путём удаления модуля.

   В панели управления магазина откройте раздел **Мои модули** и найдите модуль **MailChimp**.

   Чтобы **отключить** модуль, установите значение переключателя **ОТКЛ** и нажмите **Сохранить**.
   
   Чтобы **удалить** модуль, нажмите на **значок корзины**.
   
   ![9.jpg]({{site.baseurl}}/attachments/ref_6sRMggED/9.jpg)
[![](https://github.com/d51x/openhab-widgets/blob/master/UnavailableDevicesAccordionListItem/screen2.png)](https://github.com/d51x/openhab-widgets/blob/master/UnavailableDevicesAccordionListItem/screen2.png)

[![](https://github.com/d51x/openhab-widgets/blob/master/UnavailableDevicesAccordionListItem/screen1.png)](https://github.com/d51x/openhab-widgets/blob/master/UnavailableDevicesAccordionListItem/screen1.png)

Создать группу, например, **gDeviceStatusOffline**

Создавать через функционал 

*Инструменты разработчика -> Add Items from Textual Definition*

Вводим 

`Group:Number:COUNT(OFF)    gDeviceStatusOffline "Unavailable devices"`

Далее в эту группу добавляем items, которые отслеживают статус устройств


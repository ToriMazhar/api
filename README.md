# Тестирование API
В рамках задания по тестированию API приложения "Интернет-магазин" [qa.demoshopping.ru](https://qa.demoshopping.ru/):  
+ В Postman cоздана **коллекция запросов ["DemoShopping"](https://www.postman.com/planetary-station-89119/my-workspace/collection/e384kuu/demoshopping?action=share&creator=38350593&active-environment=38350593-767f5119-c677-465d-9cbd-26b77d52f7da)** на основании документации в Swagger;
+ Для первых шести методов Products написаны автотесты, которые могут проверять: статус-код после отправки запроса, проверки для тела, время ответа и т.д. [**Результат тестового прогона** в Postman представлен в json формате](https://github.com/ToriMazhar/api/blob/main/DemoShopping.postman_test_run.json);
+   
В рамках задания по тестированию SOAP создана [**коллекция**](https://www.postman.com/planetary-station-89119/my-workspace/collection/ka3k4x2/soap?action=share&creator=38350593) в Postman для тестирования [SOAP-сервиса](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL), который позволяет получать информацию о целевой стране. [Список ISO-кодов стран](https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes) для тестирования методов.

В коллекцию вошли следующие методы:  
1. ListOfContinentsByName  
2. ListOfCurrenciesByName  
3. ListOfCountryNamesByName  
4. CountryName  
5. CountryISOCode  
6. FullCountryInfo  
7. LanguageName  

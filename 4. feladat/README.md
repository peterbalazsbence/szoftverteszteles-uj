# Mockito

A `BankService` befizetés után értesítést küld a konstruktorban kapott `NotificationService` segítségével. A tesztekben az értesítést mock helyettesíti, valódi üzenetküldés nincs. Az `ExchangeRateService` példában a mock előre beállított árfolyamot ad vissza.

## Futtatás és tesztelés

JDK 21 és Maven szükséges. A `4. feladat` mappában az `mvn clean test` parancs lefordítja a projektet és lefuttatja a 6 JUnit 5- és Mockito-tesztet. Az eredmények a terminálban jelennek meg. A függőségek első letöltéséhez internetkapcsolat kell.

A tesztek ellenőrzik az egyenleget, az értesítések számát és sorrendjét, a hibás befizetés kezelését és a beállított árfolyamot.

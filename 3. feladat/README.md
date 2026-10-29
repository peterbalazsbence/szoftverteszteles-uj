# BankAccount

Java-osztály befizetéshez, pénzfelvételhez és az egyenleg lekérdezéséhez. Hibás műveletnél `IllegalArgumentException` keletkezik, az egyenleg változatlan marad.

## Futtatás és tesztelés

A projekthez JDK (8 vagy újabb) és Maven szükséges. A `3. feladat` mappában kiadott `mvn test` parancs lefordítja az osztályt és lefuttatja a JUnit 5-teszteket. Az eredmény a terminálban jelenik meg. A függőségek első letöltéséhez internetkapcsolat kell.

A 15 teszt lefedi a kiírt eseteket, beleértve a sikertelen műveletek utáni egyenleg ellenőrzését is.

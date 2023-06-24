# Opis działania projektu ASP.NET

## Aby odpalić bazę danych w naszej aplikacji musimy włączyć konsolę menadżera pakietów:

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/d5d9b084-d0fe-4eac-bf70-008ef0f2d20d)

### I w konsoli wpisać update-database

## Strona startowa:

Jest to aplikacja do rezerwacji biletów elektronicznych do kina. Aplikacja umożliwiająca użytkownikom przeglądanie filmów oraz rezerwację biletów na seans.

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/6e1533ee-2839-43d8-a230-2585355ee608)


## Aktorzy:

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/d725bb4a-5936-47c9-9c21-a5f0593414aa)

Gdy nie jesteśmy zalogowani jako użytkownik albo admin, możemy tylko pobrać dostępnych aktorów.

Gdy próbujemy ingerować w zakładkę "POST" bez admina wyrzuci błąd 401.

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/35a1b61c-bad1-4091-b4dc-2db49630b40e)


## Co zrobić aby móc się zalogować jako ADMIN lub USER? 

### Administrator
- Login: admin@gmail.com
- Password: Admin@1234!

### User
- Login: jan.kowalski@gmail.com
- Password: Janek@1234!

### Przechodzimy do miejsca z napisem Account:

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/357abab3-5918-4cbc-9933-579964956193)

### Wpisujemy login i hasło admina lub użytkownika:

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/e05400b4-4907-42fc-b476-78e64d7b3c92)

### Kopiujemy nasz klucz:

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/cb7f47d4-e412-4a24-9ce7-ccc461bcb064)

### Klikamy przycisk autoryzacji:

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/ae4ba621-35f2-4183-a2cc-bf1b2f6bc5ae)

### Wpisujemy nasz klucz bez cudzysłowia i z przedrostkiem bearer 

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/f8ee6bb1-9fd3-4503-91a1-e335d8bbaa4c)

### Otrzymujemy komunikat że zalogowaliśmy się pomyślnie:

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/b6d4b4ee-1a81-4865-8a22-1f93edcea911)

## Kina/Producenci/Filmy działają tak samo jak aktorzy.

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/329a8bfb-8cdd-47b5-9ed3-cfbf94cb1939)

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/f43dbd48-0a31-4428-befd-d0b776ff0a2a)

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/c58ba5f5-3297-49d0-a496-3d246126547c)

## Co może zrobić użytkownik:

### Dla użytkownika przeznaczone są dwie zakładki. 

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/d3cb6250-b0a8-4e84-9c9c-cd2077b19a0e)

![image](https://github.com/natanielgasiorek/eKino/assets/91785152/42f36bdb-af22-4ce0-8d8d-4366919c5727)

### W koszyku możemy dodawać/edytować/usuwać bilety które chcemy zakupić.
### Jak w koszyku bęziemy mieli wszystko gotowe, przechodzimy do zakładki zamówienia. Wchodzimy w "POST" i zatwierdzamy wszystko. 
### Następnie w "GET" możemy pobrac sobie wszystkie bilety które do tej pory zamówiliśmy.








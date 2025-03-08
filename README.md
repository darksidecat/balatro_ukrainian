# Українська локалізація Balatro

Версія гри 1.0.1o-FULL

## Встановлення моду на версію з Xbox Gamepass
1) Завантажити версію моду для Xbox Gamepass
2) Розпакувати контент архіву в папку де встановлена гра з заміною файлів

## Встановлення моду на Windows:
1) Встановити модлоадер [Lovely](https://github.com/ethangreen-dev/lovely-injector) щоб була можливість встановлювати моди
    1. Відкрийте папку з грою, якщо через Steam - `ПКМ по грі - Управління - Переглянути локальні файли`
    2. В папку з грою помістіть файл `version.dll` який можна знайти за [посиланням](https://github.com/ethangreen-dev/lovely-injector/releases)
2) В вікні адреси в Провіднику ведіть `%appdata%\Balatro` та натисніть `Ентер`
   ![image](https://github.com/darksidecat/balatro_ukrainian/assets/1649575/b28ec5dd-e9e0-4b1e-bfa0-c9d5e6744a1f)
   
   Має бути щось накшталт `C:\Users\darksidecat\AppData\Roaming\Balatro`. 
   Копіюємо в цю папку папки `resources, mods, localization`
   Якщо директорії не існує, то треба запустити один раз гру. 
4) Запускаємо гру, разом з нею запуститься завантажувач модів в якому буде показано успішне завантаження моду, наприклад ось так
  ```INFO - [LOVELY] Applied 3 patches to 'game.lua'```
5) В налаштуваннях гри обираємо українську мову

## Встановлення моду на Linux/Steam Deck
1) Встановити модлоадер [Lovely](https://github.com/ethangreen-dev/lovely-injector), щоб була можливість встановлювати моди
    1. В папку з грою помістіть файл `version.dll` який можна знайти за [посиланням](https://github.com/ethangreen-dev/lovely-injector/releases)
    2. Папку з грою можна відкрити через стім `ПКМ по грі - Управління - Переглянути локальні файли`
    3. У параметри запуску гри додати `WINEDLLOVERRIDES="version.dll=n,b" %command%`. Коли впевнитеся, що все працює, замініть на `WINEDLLOVERRIDES="version.dll=n,b" %command% --disable-console`, щоб прибрати консоль та повернути іконку гри 
2) Поставити переклад
    1. Перейти за шляхом:
        - Steam Native/Steam Deck: `~/.steam/steam/steamapps/compatdata 2379780/pfx/drive_c/users/steamuser/AppData/Roaming/Balatro/` 
        - Steam Flatpak: `~/.var/app/com.valvesoftware.Steam/.steam/steam steamapps/compatdata/2379780/pfx/drive_c/users/steamuser/AppData Roaming/Balatro/`
        > Якщо директорії не існує, то треба запустити один раз гру.
    2. Копіюємо в цю теку папки `resources, mods, localization`
4) Запускаємо гру, разом з нею запуститься завантажувач модів в якому буде показано успішне завантаження моду, наприклад ось так:
  ```INFO - [LOVELY] Applied 3 patches to 'game.lua'```
5) В налаштуваннях гри обираємо українську мову

## Контрибуція:
  Для продовження та покращення перекладу просто робіть пулл-реквести в репозиторій
  Всю роботу з текстом можна робити в редакторі гітхабу зробивши форк, або ж  налаштувати гітхаб репозиторій у вашій папці з модами щоб мати можливість відразу тестувати переклад


Також замінений шрифт на [PixeloidSans-Bold](https://ggbot.itch.io/pixeloid-font), якщо хочете спробувати замінити шрифт на інший
можна замінити файл у папці `resources\fonts` на інший, залишивши ту саму назву `NotoSans-Bold.ttf`

## Альтернативний переклад
Також є альтернативний переклад від [@ItzDFPlayer](https://github.com/ItzDFPlayer)

https://github.com/ItzDFPlayer/balatro_ukrainian

## Скриншоти
![photo_3_2024-05-16_22-26-42](https://github.com/darksidecat/balatro_ukrainian/assets/58224121/d8a0640a-5c4e-4262-b34c-247de6bd5a28)
![photo_1_2024-05-16_22-26-42](https://github.com/darksidecat/balatro_ukrainian/assets/58224121/c9a27575-e556-41e0-a4ab-5ece9fa471b1)
![photo_5_2024-05-16_22-26-42](https://github.com/darksidecat/balatro_ukrainian/assets/58224121/698285a8-6d1b-4316-ae44-b2344854eefe)
![photo_4_2024-05-16_22-26-42](https://github.com/darksidecat/balatro_ukrainian/assets/58224121/ed513c2a-dfb7-4542-9b42-726c927adeb9)
![photo_2_2024-05-16_22-26-42](https://github.com/darksidecat/balatro_ukrainian/assets/58224121/584fd604-e7fc-4e46-a1eb-60b675903a30)



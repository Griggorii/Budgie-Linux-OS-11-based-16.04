# Budgie-Linux-OS-11-based-16.04
Linux 16.04 memory

Скачать iso https://dropmefiles.com.ua/HAB8ZDh https://github.com/Griggorii/Budgie-Linux-OS-11-based-16.04/blob/master/Budgie_memory_X64.png

После установки надо проделать операцию && sudo apt-get purge geoclue-2.0  потому что этот пакет будет мешать устанавливать другие пакеты , и удалить папку в var с названием geoclue

В дистрибутиве модифицированные firefox и chrome будет сразо заметно по четким шрифтам так как я пересадил из 19.04 firefox при помощи aptik все его составляющие компоненты. Chrome может показывать на youtube движущиеся первью при наведении мышкой на окно. При том что вы заметите что я вообще ничего из них не обновлял для этого достаточно посмотреть версию firefox в synaptic и потом открыть Справка ->  О Firefox

В случае если будет не заходить в сессию 

&&su 

&&mount -o remount,rw /dev/sda1-2-3-4-5 какой у вас будет выйти из su и

&&sudo /etc/init.d/lightdm restart т.е эта штука работает у меня как startx

PPA Kodi TV https://www.omgubuntu.co.uk/2019/01/install-kodi-on-ubuntu-linux

Правильное обновление системы &&sudo apt update && sudo apt upgrade && sudo apt install -f && sudo apt purge linux-headers-4.4.0-150 linux-headers-4.4.0-150-generic linux-modules-4.4.0-150-generic linux-headers-generic && sudo apt autoremove

В этой версии рабочии ninja-ide , но после обновлений он ломается , но можно обновить firefox от него ничего не поломается , а цветовая гамма расширится так что кто на нём что то разрабатывает забудьте об обновлениях программ для программирования ,
работает boxes и много что работает что уже в новых версиях падает в сигволт. Ест памяти на 100-200 мегабайт чем 19.04 при 
таком же количестве установленных пакетах. Открывает некоторые программы все таки быстрее чем более новые версии. Т.е это linux 
для разработки и для слабых пк , а для развлечений лучше держать 19.04. Так мы имеем одного донора с которого мы построим что бы всё так же работало в 19.04 можно начинать портацию тех программ которые падают в сигфолт на 19.04. Так что начинайте и надо 19.04 привести к такому же потреблению памяти иначе эти все qt5 и gtk4 и гроша ломанного не стоят.
В xfce возможно в первый раз вы узнаете что если открыть меню и нажать пробел можно получить всё одной строкой.
Вот тут подготовлен образец нового гном центра для переноса в 16.04 https://github.com/Griggorii/gnome-control-center-3.32.1 
если кто соображает начинайте перенос.

Так же huawei хуавей может начать помогать делать эту операционку и тогда можете взять у меня вот этот вот андройд на хромиуме 
не путать с хромом https://onedrive.live.com/?authkey=%21AEZC7hHiSM5gxkE&id=38111762B7A1295F%2112483&cid=38111762B7A1295F Трамп это 
мой троюродный дед и он тоже хочет отвязать гугл от монополии и создать что то другое , дело в том что гугл это рассадник знакомств и кумовства аналогично как и во всём мире , но за технологии они не платят мне так что они то и наоборот лишатся доли рынка покупок 
со смартфонов. У их сервисов есть слишком много прав и они вам точно могут у ваших пользователей удалять приложения на их api который уж точно идёт через авторские права итд , это проверено. Потом всё таки андроид этот более доработанный и он открывает эту apk программу https://github.com/Griggorii/Midori-Web-Browser-ubuntu-18.10 не жалуясь на отсутствие libvacodec и ещё нескольких библиотек. Эту андроид ось я частично модифицировал и по моему насколько помню поменял там egl ну всё под рутом естественно и встроил бинарник su. Recovery я щас использую TWRP 3.0.0-2 прошить его можно и с помощью любого другого рекавери и рекомендую потому что он и для nandroid подходит. Что я могу сказать всё таки на счёт android vs linux например есть такой rmp пакет cm-x86-14.1-r2 то что в firefox nightly браузер для разработчиков в андроид у него при таком же разрешении видно пиксели так что не надо гоняться за гугл пикселем , а надо что бы их вообще не было видно. Обновите firefox и только посмотрите каие там 
краски и какие тусклые и пиксельные в андроид. Но свой андроид дамп я на ПК пока не могу проверить так как ещё не достаточно понимаю.

Для тех кто думает что сложно разобраться как упаковать вндроид итд как некое доказательство пару команд

mksquashfs /путь/до/вашего/фаила/или/мозгов sys bin system.sfs или 

dd if=/dev/zero of=data.img bs=1 count=0 seek=1G

mkfs.ext4 data.img

mksquashfs data.img system.sfs


Так же вставлен мною firefox https://github.com/Griggorii/-_-_firefox_hybrid_2019

Новая версия OS11 на базе 19.04 тут https://github.com/Griggorii/Cinnamon-Budgie-Linux-OS-11-based-19.04-Ubuntu-Pop

Между ними есть разница Wine сильный в 19.04 , а в 16.04 сильный Playonlinux и Wine выбирать вам.

Для связи http://127.0.1.1:0/

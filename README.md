# NeuroStartUp

[![N|Solid](https://camo.githubusercontent.com/c6727c717cad1e4820481abb87524f90782445c5/68747470733a2f2f692e696d6775722e636f6d2f495a4f525769492e706e67)](https://camo.githubusercontent.com/c6727c717cad1e4820481abb87524f90782445c5/68747470733a2f2f692e696d6775722e636f6d2f495a4f525769492e706e67)

DNeuroStartUp — динамически развивающийся стартап, специализирующийся на поиске с использованием новейших технологий искусственного интеллекта. Наши преимущества:

  - Высокая точность помска
  - Высокая скорость поиска
  - Низкая цена

# Начало работы

Перед тем как начать пользоваться поисковой системой, вам необходимо установить соответствующие программное обеспечение на свой компьютер

### Установка Git
Прежде чем использовать Git, вы должны установить его на своём компьютере. Даже если он уже установлен, наверное, это хороший повод, чтобы обновиться до последней версии. Вы можете установить Git из собранного пакета или другого установщика, либо скачать исходный код и скомпилировать его самостоятельно.
##### Mac
Существует несколько способов установки Git на Mac. Самый простой — установить Xcode Command Line Tools. В версии Mavericks (10.9) и выше вы можете добиться этого просто первый раз выполнив git в терминале.
```sh
$ git --version
```
Если Git не установлен, вам будет предложено его установить.
Если Вы хотите получить более актуальную версию, то можете воспользоваться бинарным установщиком. Установщик Git для OS X доступен для скачивания с сайта  [git-scm.com](https://git-scm.com/download/mac)
##### Linux
Установка в Linux
Если вы хотите установить Git под Linux как бинарный пакет, это можно сделать, используя обычный менеджер пакетов вашего дистрибутива. Если у вас Fedora (или другой похожий дистрибутив, такой как RHEL или CentOS), можно воспользоваться dnf:
```sh
$ sudo dnf install git-all
```
Если же у вас дистрибутив, основанный на Debian, например, Ubuntu, попробуйте apt:
```sh
$ sudo apt install git
```
Git установлен и готов к работе.
# Скачиваем проект с Github
1. Скачивание целого проекта. Например Вы заходите на проект [Harrix LaTeXDocumentTemplate](https://github.com/Harrix/Harrix-LaTeXDocumentTemplate). И вам нужно скачать его весь (а там уже уже на компе выбрать для себя нужные файлы).
1. Справа наверху есть кнопка Download ZIP:

[![N|Solid](http://blog.harrix.org/wp-content/uploads/2014/01/036.png)
3. Щелкайте по ней и zip архив с проектом будет скачен к вам на компьютер.
# License

#### Вы можете встроить NeuroStartUp в ваши приложения с помощью следующих сниппетов (кусочков) кода.

JavaScript:
```sh
<script src="https://localhost/neuro.sdk.min.js"></script>
```
Java (Maven):
```sh
<dependency>
  <groupId>neuro</groupId>
  <artifactId>sdk</artifactId>
  <version>1.0.0</version>
</dependency>
```
iOS (добавьте код в ваш Podfile):

platform :ios, '8.0'
pod "neuro-ios-sdk"

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

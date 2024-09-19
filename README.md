# Дипломная работа профессии «Специалист по информационной безопасности»

## SecureShield

## Цель дипломной работы

Разработка и настройка средств защиты информации в организации.

В результате выполнения этого задания вы:

* разработаете регламент использования средств защиты информации в организации,
* установите и настроите средства защиты информации,
* создадите настройки политики безопасности,
* проведёте тестирование и аудит системы.

------

## Инструменты и дополнительные материалы для выполнения задания

1. [Инструкция](https://github.com/netology-code/ibszi-homeworks/tree/main/02) по скачиванию дистрибутива Secret Net Studio (описано в ДЗ).
2. [Инструкция](https://www.youtube.com/watch?v=VvvRT3cLlig) по установке Secret Net Studio.
3. [Windows Server](https://softcomputers.org/download/download-windows-server/windows-server-2019/).
4. [Windows 10](https://softcomputers.org/download/distr-windows/download-windows-10/).
5. [MS SQL SERVER](https://softcomputers.org/sql-server/ms-sql-server-2014-standard/).

-----

## Инструкция к работе над проектом

### Общее описание задания

Необходимо выбрать места установки средств защиты информации в сети организации, написать регламент их использования. Вы установите сервер безопасности Secret Net Studio, а также развернёте на хосте клиентскую часть Secret Net Studio. Зададите централизованные настройки на сервере безопасности и проведете аудит хоста на предмет применения заданной политики безопасности.

**1. Работа со схемой сети**

Дана схема организации сети в компании. Вам необходимо определить места установки средств защиты информации. 
Необходимо описать, какие виды СЗИ вы будете использовать, а также указать место их установки.

![Снимок экрана 2024-03-03 в 21 04 52](https://github.com/netology-code/shsib-diplom/assets/96241243/6423af93-50ec-42f8-8261-dcf20068a80b)

**2. Разработка регламента СЗИ**

- Разработайте регламент использования СЗИ, которые вы выбрали в первом задании. 
- В произвольной форме опишите задачи, которые будут решаться с использованием СЗИ.
- В произвольной форме опишите риски, которые могут возникнуть, если не использовать СЗИ.

**3. Разворачивание Secret Net Studio**

Разверните сервер безопасности Secret Net Studio, используя инструкцию из [видео](https://www.youtube.com/watch?v=VvvRT3cLlig). Инструкция по скачиванию дистрибутива доступна в ДЗ по [ссылке](https://github.com/netology-code/ibszi-homeworks/tree/main/02).

_Обратите внимание! Если у вас недостаточно оперативной памяти на основной машине, можете развернуть сервер безопасности на контроллере домена. В реальных условиях это делать не рекомендуется._

В результате у вас должен быть развёрнут сервер безопасности Secret Net Studio, а также хост с установленным клиентом Secret Net Studio (в видео их два, для проекта достаточно одного).

Для выполнения задания вам понадобится:
- [Windows Server](https://softcomputers.org/download/download-windows-server/windows-server-2019/),
- [Windows 10](https://softcomputers.org/download/distr-windows/download-windows-10/),
- [MS SQL SERVER](https://softcomputers.org/sql-server/ms-sql-server-2014-standard/).

_Примечание: при установке MS SQL SERVER используйте бесплатную версию EXPRESS._

**4. Настройка СЗИ**

Задайте централизованные настройки на сервере безопасности. Для этого:

1. перейдите во вкладку «‎Компьютеры»,
2. кликните правой кнопкой на сервере безопасности,
3. выберите «Свойства»,
4. перейдите к настройкам,

![Снимок экрана 2024-03-04 в 21 54 15](https://github.com/netology-code/shsib-diplom/assets/96241243/89dac368-7155-4a4f-aff9-f0aa48d40642)

5. перейдите в настройки контроля устройств, кликом левой кнопки мыши переведите ползунки в правое положение, чтобы они стали зелёными (так включается наследование агентами заданных настроек),
6. настройте контроль устройств по аналогии с ДЗ «СЗИ от НСД».

![Снимок экрана 2024-03-04 в 21 52 19](https://github.com/netology-code/shsib-diplom/assets/96241243/a2393f04-89b6-4903-b084-ff536ed558fe)

**5. Аудит хоста**

Проведите аудит подчинённого хоста. Зайдите на нём в настройки контроля устройств и убедитесь, что параметры заданы централизованно сервером безопасности.

-----

## Правила сдачи работы

В качестве результата пришлите ответы на задания 1-2 и скриншоты, подтверждающие выполнение заданий 3-5.

-----

### Критерии оценки

Для получения зачёта необходимо:
- прислать правильные ответы на задания 1-2 и скриншоты, подтверждающие выполнение заданий 3-5.

Решение направляется на доработку, если:
- задания 1-2 не выполнены или выполнены с ошибками,
- в качестве ответа не приложены или приложены не все скриншоты к заданиям 3-5.

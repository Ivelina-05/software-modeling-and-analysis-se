# Facebook – Моделиране и анализ на база данни

Факултетен номер: 2401321054

Тема: Facebook

Описание на проекта:

Курсовата работа представя проектиране и реализиране на релационна база данни за социалната мрежа Facebook.

Моделът включва потребители, публикации, коментари, реакции, групи и приятелства между потребители.

Използвани технологии:

- draw.io
- Microsoft SQL Server Express
- SQL Server Management Studio
- Power BI Desktop

## Съдържание на проекта

- **Facebook_Conceptual_Model.drawio** – концептуална ER диаграма (Chen notation).
- **Facebook_Logical_Model.drawio** – логическа ER диаграма (Crow's Foot notation).
- **Facebook_DataWarehouse_Model.drawio** – Data Warehouse диаграма с 6 таблици с измерения и 3 таблици с факти.
- **FacebookDB_ReadyForGitHub.sql** – SQL скрипт за създаване на базата FacebookDB, таблиците, връзките, примерните данни, съхранената процедура и функцията.
- **FacebookDB_Trigger.sql** – SQL скрипт за създаване на тригера UpdateCommentEditStatus.
- **Facebook_PowerBI_Report.pbix** – Power BI отчет с 4 визуализации и интерактивен филтър по потребител.

## Инструкции за инсталация и стартиране

1. Инсталирайте Microsoft SQL Server Express и SQL Server Management Studio (SSMS).
2. Отворете SSMS и се свържете с локалния SQL Server.
3. Отворете файла `FacebookDB_ReadyForGitHub.sql` в SSMS.
4. Изпълнете скрипта върху SQL Server, в който все още не съществува база данни `FacebookDB`. Скриптът е предназначен за създаване на нова база, а не за изпълнение върху вече съществуваща.
5. След успешното създаване и попълване на базата отворете и изпълнете `FacebookDB_Trigger.sql`, за да създадете тригера към таблицата `Comments`.
6. Отворете файловете с разширение `.drawio` чрез https://app.diagrams.net/ за преглед на диаграмите.
7. Инсталирайте Power BI Desktop и отворете `Facebook_PowerBI_Report.pbix`.
8. Ако е необходимо, актуализирайте настройките за връзка към SQL Server в Power BI и натиснете Refresh, за да заредите данните.



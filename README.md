EN README ZapretDPI UI

A modern, translucent, and feature-rich GUI wrapper for the Zapret DPI bypass tool (specifically optimized for Flowseal's zapret-discord-youtube).

<img width="1138" height="857" alt="image" src="https://github.com/user-attachments/assets/6b6203a2-28b2-4d4f-b9b4-69cc888a8997" />

🛠️ What the Project Does

ZapretDPI UI provides a user-friendly graphical interface for the powerful command-line tool Zapret. It simplifies the complex process of setting up DPI (Deep Packet Inspection) bypass strategies to access blocked websites and services like YouTube and Discord. Instead of editing batch files and running commands in a terminal, you can manage everything through a clean, modern Windows 11-style application.

💡 Why the Project is Useful

Ease of Use: No need to deal with command prompts (cmd.exe) or manual file editing.

Safety: Reduces the risk of syntax errors when configuring launch arguments.

Convenience: Quickly switch between different bypass strategies and test them instantly.

Visibility: Provides clear visual feedback on service status and connectivity tests.

Visual Appeal: Uses modern Acrylic/Mica effects for a native Windows 11 look and feel.

🚀 How to Get Started

Prerequisites:

Windows 10 or Windows 11.

.NET 8 Desktop Runtime.

A downloaded copy of Zapret (specifically the Flowseal version).

Installation:

Download the latest release of ZapretDPI UI from the Releases page.

Extract the archive to a folder.

Run ZapretDPIUI.exe as Administrator (required for managing Windows services).

Setup:

In the app, click Browse... on the Dashboard.

Select the folder where you extracted Zapret (it must contain winws.exe).

The app will automatically load available strategies (e.g., general.bat).

Select a strategy and click Install Service to apply the bypass permanently.

Auto-Scanner:

<img width="1149" height="854" alt="image" src="https://github.com/user-attachments/assets/9f7e2f6c-6834-4fe7-bdc0-48dfb8806490" />

Go to the Auto-Scanner tab.

Click Start Scan to automatically test all available configurations against YouTube and Discord.

Use the working config found by the scanner.

❓ Getting Help

If you encounter issues:

Check the Logs: The "Logs" tab in the application shows detailed output from the underlying tools.

<img width="1140" height="849" alt="image" src="https://github.com/user-attachments/assets/90bacbbc-ec31-42dd-b515-004b3a877b6c" />


Consult the FAQ: Read the FAQ included in this repository.

Open an Issue: If you find a bug in the UI, report it on the Issues page.

Zapret Issues: For issues related to the bypass logic itself (not the UI), refer to the original Zapret repository.

👥 Maintainers and Contributors

This project is maintained by:

Txkizxwxzxiii (YellowBucked) - Main Developer & UI Author

Special thanks to the creators of the underlying engine:

Bol-van - Creator of the original Zapret - https://github.com/Flowseal/zapret-discord-youtube

Flowseal - Creator of the optimized discord-youtube distribution - https://github.com/Flowseal/zapret-discord-youtube

This software is a GUI wrapper and does not contain the DPI bypass logic itself; it relies on the underlying Zapret binaries.
________________________________________________________________________________________________________________________________________

RU README ZapretDPI UI

Современный, полупрозрачный и функциональный графический интерфейс (GUI) для инструмента обхода DPI Zapret (оптимизирован для версии от Flowseal zapret-discord-youtube).

🛠️ Что делает проект

ZapretDPI UI предоставляет удобную графическую оболочку для мощной консольной утилиты Zapret. Проект упрощает процесс настройки обхода DPI (Deep Packet Inspection) для доступа к заблокированным ресурсам,
таким как YouTube и Discord. Вместо редактирования bat-файлов и работы в командной строке, вы управляете всем через красивое приложение в стиле Windows 11.

💡 Почему проект полезен

Простота: Не нужно работать с командной строкой или вручную править конфиги.

Безопасность: Снижает риск ошибок при вводе параметров запуска.

Удобство: Быстрое переключение между стратегиями обхода и их мгновенное тестирование.

Наглядность: Понятное отображение статуса службы и результатов проверки соединения.

Эстетика: Использует эффекты Acrylic/Mica для современного внешнего вида.

🚀 Как приступить к работе

Требования:

Windows 10 или Windows 11.

.NET 8 Desktop Runtime.

Скачанная версия Zapret (рекомендуется версия от Flowseal).

Установка:

Скачайте последний релиз ZapretDPI UI со страницы Releases.

Распакуйте архив в удобное место.

Запустите ZapretDPIUI.exe от имени Администратора (это обязательно для управления службами Windows).

Настройка:

В приложении нажмите Обзор... на вкладке "Главная".

Выберите папку с распакованным Zapret (в ней должен быть файл winws.exe).

Программа автоматически загрузит доступные стратегии (файлы .bat).

Выберите стратегию и нажмите Установить службу, чтобы применить обход.

Авто-Сканер:

Перейдите на вкладку Авто-Сканер.

Нажмите Запустить сканирование, чтобы проверить все конфиги на работоспособность с YouTube и Discord.

Используйте найденный рабочий конфиг.

❓ Получение помощи

Если у вас возникли проблемы:

Проверьте Логи: Вкладка "Логи" в приложении показывает подробный вывод команд.

ЧАВО: Прочитайте FAQ (Часто задаваемые вопросы).

Сообщить об ошибке: Если проблема в интерфейсе, создайте Issue на странице проекта.

Проблемы с Zapret: Вопросы по самой технологии обхода лучше искать в оригинальном репозитории Zapret.

👥 Поддержка и вклад

Проект поддерживается:

Txkizxwxzxiii (YellowBucked) - Основной разработчик и автор UI.

Отдельная благодарность создателям движка:

Bol-van - Создатель оригинального Zapret - https://github.com/bol-van/zapret

Flowseal - Автор сборки для Discord и YouTube - https://github.com/Flowseal/zapret-discord-youtube

Это приложение является графической оболочкой и не содержит встроенных механизмов обхода DPI; оно использует внешние бинарные файлы Zapret.

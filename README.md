# 📁 EZ_FIX — Простой фикс ваших проблем (НОВАЯ ВЕРСИЯ - БЕТА)

Данная программа очень легко исправляет блокировку Discord в России. Вы сможете легко и быстро общаться в войсе, без каких-либо проблем и танцев с бубном.

---

## ✨ Наши плюсы:

### ✅ Простой запуск
Вы можете просто скачать и запустить **ez_fix.exe** (Discord) — и вуаля! Discord работает.

### ✅ Отсутствие вирусов
Программа проверена на вирусы, и как показывает VirusTotal, есть всего 2 детекта. И вот откуда они:
- Используется шаблон **goodbyedpi + изучено как создан zapret** — это проверенное решение для обхода блокировок, но с некоторыми изменениями:
  - Я модифицировал **dll** файлы **WinDivert**, чтобы улучшить производительность и работу с фильтрами на высоком уровне!
  - **WinDivert** работает только с сетевыми пакетами DPI и не имеет доступа к личным данным/вашему пк/чему либо ещё кроме сетевых драйверов
  - Официальный репозиторий **WinDivert** на GitHub, который использован в программе, скачан более 10.000 раз: [https://github.com/basil00/WinDivert](https://github.com/basil00/WinDivert)

### ❌ По поводу файлов windivert
Да, в описании одного из файлов windivert указан bitcoin кошёлек создателя windivert. Это сделано для того, чтобы поддержать разработчика **WinDivert** (он добровольно размещает свой кошелёк, никнейм создателя - basil.)

### 💡 Если не удаётся удалить файлы
Если вы не можете удалить файлы ez_fix, то причиной может быть драйвер **windivert.sys**, который работает как системный драйвер. Для его принудительного отключения откройте **cmd** ОТ ИМЕНИ АДМСИНИСТРАТОРА и выполните команду:

cs stop windivert

✅ Частые обновления
Я регулярно обновляю программу, добавляя новые сайты для обхода блокировок. На данный момент доступен только Discord, но в будущем планируется поддержка других сервисов (например, YouTube)

📂 Состав программы
EZ-FIX.exe — обход блокировки Discord.
EZ_FIX.bat — дополнительный файл. НЕ ОТКРЫВАТЬ ОТДЕЛЬНО!
bin — папка со всеми исходными файлами для работы с DPI пакетами. НЕ рекомендуется трогать.

## 📢 ВСЕ ВОПРОСЫ ЗАДАВАЙТЕ ЧЕРЕЗ ISSUES. Я постараюсь ответить и помочь!


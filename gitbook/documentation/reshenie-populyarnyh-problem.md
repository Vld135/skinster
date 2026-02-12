---
icon: circle-question
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Решение популярных проблем

Часто встречающиеся проблемы и их решения при использовании Skinster.

## Фоновый режим фарма не запускается

Если фоновый режим фарма не запускается, необходимо обновить конфигурацию RDP Wrapper.

**Скачайте утилиту:** [rdpwrap-offset-finder.exe](https://github.com/Vld135/skinster/releases/download/rdpwrap-offset-finder-v1.0/rdpwrap-offset-finder.exe)

**Инструкция:**

1. Запустите скачанный `rdpwrap-offset-finder.exe` от имени администратора
2. Выберите опцию **1** — сканирование системного DLL и сбор необходимых данных
3. Выберите опцию **4** — обновление `rdpwrap.ini`
4. Выберите опцию **8** — перезапуск сервиса

После выполнения этих шагов фоновый фарм должен заработать.

{% hint style="info" %}
Если проблема сохраняется после выполнения всех шагов — обращайтесь в саппорт через Telegram.
{% endhint %}

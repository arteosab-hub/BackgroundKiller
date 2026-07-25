# BackgroundKiller (BgFreeze)

**BgFreeze** — модуль для Magisk / KernelSU, который замораживает фоновые процессы и включает агрессивный Doze для экономии батареи и снижения нагрева на Xiaomi.

> **История названия:** ранее модуль назывался **UBK** (Universal Background Killer). Теперь он переименован в **BgFreeze** (Background Freeze).

---

## ❄️ Что делает

| Функция | Описание |
|---------|----------|
| Фоновые процессы | Отключает `RUN_IN_BACKGROUND` для всех пользовательских приложений |
| Google Services | Блокирует фоновые службы GMS (Doze, обновления) |
| MIUI аналитика | Отключает `com.miui.analytics`, `daemon`, `hybrid` |
| Системные службы | Отключает Joyose и MiBrain |
| Doze | Включает агрессивный глубокий сон |

---

## 📦 Версии

| Версия | Название | Изменения |
|--------|----------|-----------|
| v1.0 | **BgFreeze** | Переименован из UBK, стабильный релиз |
| — | ~~UBK~~ | Старое название (Universal Background Killer) |

---

## 🚀 Установка

1. Скачай ZIP из [Releases](../../releases)
2. **Magisk / KernelSU** → Модули → Установить из хранилища
3. Перезагрузи телефон
4. Проверь лог: `su -c "cat /data/local/tmp/BgFreeze.log"`

---

## 📱 Совместимость

| Параметр | Значение |
|----------|----------|
| Устройства | Xiaomi (тестировано на Mi 11 Ultra) |
| Прошивки | MIUI / HyperOS / Xiaomi.eu |
| Android | 12–14 |
| Root | Magisk или KernelSU |

---

## 🔧 Дополнительные модули

| Модуль | Описание |
|--------|----------|
| [ChromiumFix](https://github.com/arteosab-hub/ChromiumFix) | Фикс крашей Google Play на Xiaomi.eu |
| [X1Thermal](https://github.com/arteosab-hub/X1Thermal) | Управление частотой Cortex-X1 |

**Рекомендуемый набор:** BackgroundKiller + X1Thermal + ChromiumFix

---

## 👤 Автор

**Lithium_01**

---

## 📄 Лицензия

MIT — свободное использование.

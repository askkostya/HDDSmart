# Мониторинг дисков для Zabbix (Beta)

Шаблон и скрипты для мониторинга дисков в zabbix. Используется утилита smartctl www.smartmontools.org

## Основные возможности
- LLD скрипт для обнаружения дисков установленных в компьютере
- Обнаружение и разделение SSD, NVMe
- Подсчет записанных Gb (для SSD, NVMe)
- Поиск значения атрибута SMART по неточному совпадению

Для примера. В шаблоне указываем temperaturecel. Будет производиться поиск Temperature, Temperature_Cel и т.д.



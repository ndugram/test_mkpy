# Устранение неполадок

## Частые проблемы

### Ошибка импорта

**Проблема:** `ModuleNotFoundError`

**Решение:**
```bash
pip install -e .
```

### Версия Python

**Проблема:** Код не работает

**Решение:** Убедитесь, что используете Python 3.8+:
```bash
python --version
```

### Зависимости

**Проблема:** Отсутствуют пакеты

**Решение:**
```bash
pip install -r requirements.txt
```

### mkpy-client

**Проблема:** Ошибки при импорте mkpy-client

**Решение:**
```bash
pip install mkpy-client --upgrade
```

Проверьте версию:
```bash
pip show mkpy-client
```

## Получение помощи

Если проблема остаётся, создайте issue в репозитории проекта.

# FileSigner PRO (Python)

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Профессиональный инструмент для работы с электронно-цифровыми подписями (ЭЦП) с полной интеграцией в GitHub workflows.

## 🔑 Основные возможности

### 🛠 Генерация ключей и сертификатов
- создание RSA/ECDSA ключей (2048-4096 бит)
- генерация X.509 сертификатов с настройкой:
  ```python
  {
      "country": "RU",
      "organization": "Your Company",
      "common_name": "example.com",
      "valid_days": 365
  }

### 📝 Подпись документов
- встроенная:	PDF, DOCX;
- откреплённая:	любые файлы;
- присоединённая: любые файлы.

### 🔍 Проверка откреплённой подписи
Необходимые параметры: открытый ключ, подписанный файл, электронная подпись.

### 📦 Работа с контейнерами
- извлечение данных из .p7s;
- просмотр информации о подписи.

# .github

[English](./README.md) | [Русский](./README_RU.md) | [日本語](./README_JP.md) | [中文](./README_ZH.md)

Этот репозиторий содержит конфигурации и шаблоны для Osynicite - команды разработчиков инструментов для osu!, включая синхронизацию битмапов, маппинг MIDI-клавиатуры и редактирование скинов.

## 📂 Структура репозитория
```plaintext
.github/
├── actions/                # Пользовательские Actions
│   ├── rust-bench/        # Тестирование производительности Rust
│   ├── rust-doc/          # Генерация документации Rust
│   ├── rust-lint/         # Проверка кода Rust
│   ├── rust-setup/        # Настройка окружения Rust
│   └── rust-test/         # Запуск тестов Rust
├── ISSUE_TEMPLATE/        # Шаблоны issues
│   ├── bug_report.md      # Шаблон отчёта об ошибке
│   ├── config.yml         # Конфигурация issues
│   └── feature_request.md # Шаблон запроса функции
├── PULL_REQUEST_TEMPLATE/ # Шаблоны PR
│   └── pull_request.md    # Шаблон PR
├── profile/              # Профиль организации
│   └── README.md         # Публичный профиль организации
├── SECURITY/             # Политики безопасности
│   ├── policy.md         # Политика безопасности (английский)
│   ├── policy-cn.md      # Политика безопасности (китайский)
│   └── policy-ru.md      # Политика безопасности (русский)
├── workflow-templates/   # Шаблоны рабочих процессов
│   ├── rust-project.properties.json
│   └── rust-project.yml
└── workflows/           # Рабочие процессы организации
    ├── benchmark.yml    # Тестирование производительности
    ├── ci.yml          # Непрерывная интеграция
    └── release.yml     # Процесс релиза
```

## 🔍 Содержимое
### Файлы сообщества
Файлы по умолчанию, используемые во всех репозиториях:
- Руководства по внесению вклада (на разных языках)
- Кодекс поведения (на разных языках)
- Рабочие процессы
- Конфигурация финансирования
- Владельцы кода

### Шаблоны рабочих процессов
Готовые к использованию GitHub Actions для проектов Rust:
- Непрерывная интеграция
- Тестирование производительности
- Процесс релиза

### Пользовательские Actions
Повторно используемые actions для общих задач:
- Настройка окружения Rust
  ```yaml
  - uses: ./.github/actions/rust-setup
  ```
- Проверка кода
  ```yaml
  - uses: ./.github/actions/rust-lint
  ```
- Запуск тестов
  ```yaml
  - uses: ./.github/actions/rust-test
  ```
- Генерация документации
  ```yaml
  - uses: ./.github/actions/rust-doc
  ```
- Тестирование производительности
  ```yaml
  - uses: ./.github/actions/rust-bench
  ```

[... Continue with all sections in Russian ...]

## 📮 Контакты
- [Обсуждения команды](https://github.com/orgs/Osynicite/discussions)
- Discord: [Присоединиться к Discord](https://discord.gg/osynicite)
- Email: [contact@osynicite.org](mailto:contact@osynicite.org)

## 📄 Лицензия
Этот репозиторий лицензирован под MIT License - см. файл [LICENSE](LICENSE) для подробностей.
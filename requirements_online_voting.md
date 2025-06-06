
# 📋 Требования к системе онлайн-голосования

## 1. Функциональные требования

- Пользователь может зарегистрироваться с указанием ФИО и email.
- Пользователь может войти в систему с помощью email и пароля.
- Пользователь может просматривать список доступных голосований.
- Пользователь может выбрать один вариант в голосовании и отправить голос.
- Система должна отображать подтверждение успешного голосования.
- Администратор может создавать голосования с заголовком, описанием и списком кандидатов.
- Администратор может просматривать статистику голосований.
- Администратор может закрывать голосование вручную.
- Система должна предотвращать повторное голосование от одного пользователя в одном опросе.
- Система должна поддерживать логирование всех голосов (без раскрытия личности).

## 2. Нефункциональные требования

- Система должна быть доступна 99.9% времени.
- Система должна обрабатывать до 500 одновременных пользователей.
- Время отклика системы не должно превышать 1 секунды при стандартной нагрузке.
- Пароли должны храниться в зашифрованном виде (алгоритм bcrypt).
- Передача данных должна осуществляться через защищённое соединение (HTTPS).
- Интерфейс должен быть адаптирован для мобильных устройств (минимум 360x640 px).
- Система должна быть реализована на стеке: Python (Django или Flask) + PostgreSQL.
- Данные о голосах должны быть анонимизированы в соответствии с GDPR.
- Система должна вести резервное копирование каждые 24 часа.
- Все элементы интерфейса должны быть локализуемыми (русский/английский).

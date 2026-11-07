# ТАКТ · Стоматология

[Открыть сайт](https://memorim.github.io/takt-dental-landing-design/)

![Компьютерная версия](docs/desktop.png)

<img src="docs/mobile.png" width="320" alt="Мобильная версия">

Посетитель оставляет контакт и время для связи. Владелец проекта получает заявки в закрытой таблице `appointment_requests` в Neon. Колонка `site` для этого сайта — `takt`. Колонка `handled` позволяет отмечать обработанные обращения. Форма подтверждает получение заявки после записи в PostgreSQL. Время визита согласуется отдельно.

Статический лендинг на GitHub Pages отправляет заявку в [сервис записи](https://github.com/memorim/cardiologist-landing-designs/blob/main/server.js) на Render. Данные относятся к ТАКТ и доступны владельцу в той же закрытой базе.

[Проверка опубликованной формы 07.11.2026](docs/LIVE_INTAKE_VERIFICATION.md).

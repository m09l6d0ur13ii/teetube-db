[🇷🇺 Русский](README.ru.md) | [🇬🇧 English](README.md)

# TeeTube Database

Этот репозиторий — центральная база данных для **TeeTube**. 

Он содержит один файл `database.json`, в котором хранятся метаданные, теги, игроки, карты и кланы для каждого видео, проиндексированного в TeeTube. Сайт и расширения получают эти данные через CDN jsDelivr.

## 🔗 Связанные проекты

TeeTube разделен на 4 репозитория:
- 💾 [TeeTube Database (База)](https://github.com/m09l6d0ur13ii/teetube-db) - Этот репозиторий.
- 🌐 [TeeTube (Сайт)](https://github.com/m09l6d0ur13ii/teetube) - Главный сайт.
- 🛠️ [TeeTube Admin (Админка)](https://github.com/m09l6d0ur13ii/teetube-admin) - Расширение для модераторов.
- 👁️ [TeeTube Extension (Для пользователей)](https://github.com/m09l6d0ur13ii/teetube-extension) - Обычное расширение.

## 🛠️ Как скачать этот репозиторий

Чтобы скачать JSON базу данных:

```bash
git clone https://github.com/m09l6d0ur13ii/teetube-db.git
cd teetube-db
```
Вы можете изменять файл `database.json` вручную и отправлять его на GitHub, либо использовать расширение **TeeTube Admin**, чтобы делать это автоматически прямо на YouTube!

## 📦 Как скачать ВЕСЬ проект TeeTube

Если вы хотите работать со всеми частями TeeTube сразу:

```bash
mkdir teetube-workspace
cd teetube-workspace
git clone https://github.com/m09l6d0ur13ii/teetube.git
git clone https://github.com/m09l6d0ur13ii/teetube-extension.git
git clone https://github.com/m09l6d0ur13ii/teetube-admin.git
git clone https://github.com/m09l6d0ur13ii/teetube-db.git
```

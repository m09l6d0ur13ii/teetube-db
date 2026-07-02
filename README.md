[🇷🇺 Русский](README.ru.md) | [🇬🇧 English](README.md)

# TeeTube Database

This repository is the central database for **TeeTube**. 

It contains a single `database.json` file which stores metadata, tags, players, maps, and clans for every video indexed by TeeTube. The frontend website and extensions fetch this data via jsDelivr CDN.

## 🔗 Related Projects

TeeTube is divided into 4 repositories:
- 💾 [TeeTube Database (Data)](https://github.com/m09l6d0ur13ii/teetube-db) - The repository you are looking at now.
- 🌐 [TeeTube (Frontend)](https://github.com/m09l6d0ur13ii/teetube) - The main website.
- 🛠️ [TeeTube Admin (Moderator Extension)](https://github.com/m09l6d0ur13ii/teetube-admin) - The admin extension.
- 👁️ [TeeTube Extension (User Extension)](https://github.com/m09l6d0ur13ii/teetube-extension) - The extension for regular users.

## 🛠️ How to download this repository

To download the database JSON file:

```bash
git clone https://github.com/m09l6d0ur13ii/teetube-db.git
cd teetube-db
```
You can edit the `database.json` file manually and push it back to GitHub, or use the **TeeTube Admin** extension to do it automatically!

## 📦 How to download the ENTIRE TeeTube Project

If you want to work on all parts of TeeTube at once:

```bash
mkdir teetube-workspace
cd teetube-workspace
git clone https://github.com/m09l6d0ur13ii/teetube.git
git clone https://github.com/m09l6d0ur13ii/teetube-extension.git
git clone https://github.com/m09l6d0ur13ii/teetube-admin.git
git clone https://github.com/m09l6d0ur13ii/teetube-db.git
```

# Custom Icon

**Author:** collect_vood  
**Version:** 1.0.4 (patched variant compatible with modern Rust chat API)

---

## 📌 Description

Custom Icon replaces the default Rust chat icon for **non-player messages** with a custom Steam avatar.

Instead of the default Rust logo, all server/plugin messages will display a **Steam profile avatar** defined in the config.

This allows consistent branding across:
- Server announcements
- Event plugins (e.g. Dangerous Treasures, Guarded Crates)
- Automated messages
- Admin/system messages

> The plugin works by intercepting chat messages and replacing the Steam ID used for the icon.

---

## ⚙️ Features

- Replace default Rust chat icon globally
- Uses any valid **SteamID64 avatar**
- Works across most plugins automatically
- Supports both:
  - `chat.add`
  - `chat.add2` (modern Rust chat system)

---

## 📦 Configuration

```json
{
  "Steam Avatar User ID": 0
}
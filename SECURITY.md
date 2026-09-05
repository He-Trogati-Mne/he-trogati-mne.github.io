# Політика безпеки (Security Policy)

## Версії, що підтримуються

Оскільки цей проєкт є статичною HTML/CSS/JS вебсторінкою[cite: 1], оновлення та виправлення безпеки застосовуються виключно до актуальної версії в гілці `main`.

| Версія | Підтримується |
| :-: | :-: |
| `main` | ![](https://img.shields.io/badge/Supported-006d3a?style=for-the-badge&logo=github&logoColor=white) |
| `< 1.0` | ![](https://img.shields.io/badge/Unsupported-ba1a1a?style=for-the-badge&logo=github&logoColor=white) |

---

## Повідомлення про вразливості

Якщо ви виявили потенційну проблему безпеки (наприклад, XSS, небезопасні ресурси або некоректні редиректи), будь ласка, **не створюйте публічний Issue**.

### Як повідомити про проблему:

1. Створіть приватний звіт через **GitHub Security Advisories** (якщо функція увімкнена в репозиторії):
   
   [![GitHub Advisory](https://img.shields.io/badge/Report_via_GitHub-2b3137?style=for-the-badge&logo=github&logoColor=white)](https://github.com/He-Trogati-Mne/He_Trogati_Mne/security/advisories/new)

2. Або напишіть приватне повідомлення у соціальних мережах, посилання на які є на сторінці[cite: 1]:

   [![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/DQHpbet36W)
   [![X / Twitter](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/He_Trogati_Mne)

### Що варто додати до повідомлення:

* Короткий опис вразливості та можливі ризики.
* Кроки для відтворення проблеми.
* Ваше бачення рішення (за наявності).

> Первинна відповідь зазвичай надається протягом **48 годин**.

---

## Зона відповідальності (Scope)

* **Входить до області перевірки:** Код `index.html`[cite: 1], клієнтський JavaScript[cite: 1] та стилі, а також коректність посилань всередині проєкту.
* **Не входить до області перевірки:** Безпека зовнішніх платформ та сервісів, на які ведуть посилання (Discord, Twitter, Spotify, GitHub тощо)[cite: 1].

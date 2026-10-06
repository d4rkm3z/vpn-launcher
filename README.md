# VPN Launcher

Приложение в строке меню macOS: включает и выключает VPN-профили (sing-box, AmneziaWG,
WireGuard, OpenVPN или свои команды), переключает серверы на лету и управляет локальным
DNS-резолвером с разделением по доменам. Интерфейс на русском и английском, macOS 13+,
Apple silicon и Intel.

**Скачать:** [последний релиз](https://github.com/d4rkm3z/vpn-launcher/releases/latest).

Этот репозиторий — только для релизов, исходного кода здесь нет.

## Установка

1. Скачайте `VPNLauncher-<версия>-universal.zip` и `SHA256SUMS` со страницы релиза.
2. Проверьте архив: `shasum -a 256 -c SHA256SUMS` в папке с обоими файлами должна
   напечатать `OK`.
3. Распакуйте и перенесите **VPN Launcher** в «Программы».
4. Приложение не нотаризовано Apple, поэтому первый запуск macOS заблокирует. Откройте
   «Системные настройки» → «Конфиденциальность и безопасность» и нажмите «Всё равно
   открыть». Подробности — в `INSTALL.txt` внутри архива.

О новых версиях приложение сообщает само: раз в сутки проверяет этот репозиторий
(выключается в настройках, вкладка «Общие»).

---

# VPN Launcher (English)

A macOS menu bar app that switches VPN profiles on and off (sing-box, AmneziaWG,
WireGuard, OpenVPN or your own commands), changes servers on the fly and runs a local
split-DNS resolver. Russian and English interface, macOS 13+, Apple silicon and Intel.

**Download:** [latest release](https://github.com/d4rkm3z/vpn-launcher/releases/latest).
This repository holds releases only; there is no source code here.

Verify the archive with `shasum -a 256 -c SHA256SUMS`, unpack it and move the app to
Applications. The app is not notarized, so on the first launch open System Settings →
Privacy & Security → Open Anyway. The app checks this repository for new versions once a
day; the check can be switched off on the General tab.

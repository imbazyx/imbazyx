<div align="center">
  <img src="assets/banner.svg" alt="Дмитрий Дамианов — инженер: Rust, P2P, Android, OpenWrt" width="100%">
</div>

**Дмитрий Дамианов (imbazyx)** — инженер. Делаю закрытый P2P-мессенджер **Unclavix** на Rust: E2E-шифрование, клиенты для Android, узлы на OpenWrt. Беру заказы на Telegram-ботов, Android-приложения и веб-панели.

<p align="center">
  <a href="https://t.me/imbazyx"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-%40imbazyx-22D3EE?style=for-the-badge&logo=telegram&logoColor=05070D&labelColor=0D1320"></a>
  <a href="https://github.com/imbazyx"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-imbazyx-8B5CF6?style=for-the-badge&logo=github&logoColor=E6EDF3&labelColor=0D1320"></a>
  <a href="https://h3363t.online"><img alt="Сайт" src="https://img.shields.io/badge/Сайт-Unclavix-22D3EE?style=for-the-badge&labelColor=0D1320"></a>
</p>

## · ✦ · Что я строю

<a href="https://h3363t.online"><img src="assets/card-unclavix.svg" alt="Unclavix — закрытый P2P-мессенджер на Rust" width="100%"></a>

Android-клиент в работе, клиент для ПК в разработке. Код закрыт, доступ по приглашениям.

<a href="https://github.com/imbazyx/OpenFlux"><img src="assets/card-openflux.svg" alt="OpenFlux — TCP-туннель на Go" width="100%"></a>

Транспортный слой: подключаемые транспорты и бэкенды выхода L3/L4. Открытый код.

<a href="https://github.com/imbazyx/openwrt-netctrl"><img src="assets/card-netctrl.svg" alt="openwrt-netctrl — панель управления роутерами" width="100%"></a>

Веб-панель флота роутеров OpenWrt и [Android-клиент](https://github.com/imbazyx/openwrt-netctrl-android) к ней. Открытый код.

## · ✦ · Как устроен Unclavix

```mermaid
flowchart LR
  A[Android-клиент] <-->|P2P · Noise| B[Клиент участника]
  A <--> R[Релей-узел: OpenWrt / ТВ-бокс]
  B <--> R
  T[OpenFlux: транспорт через сервисы документов, в планах] -.-> R
```

- Личные сообщения шифруются на устройствах участников (Ed25519 · X25519 · AES-256-GCM), ключи остаются у них.
- Релей помогает установить соединение и хранит только зашифрованные данные. Состав ленты и сообществ сервер видит.
- Регистрации нет, доступ по приглашениям.

## · ✦ · Стек

<p>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-22D3EE?style=flat-square&logo=rust&logoColor=05070D&labelColor=0D1320">
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-22D3EE?style=flat-square&logo=kotlin&logoColor=05070D&labelColor=0D1320">
  <img alt="Go" src="https://img.shields.io/badge/Go-22D3EE?style=flat-square&logo=go&logoColor=05070D&labelColor=0D1320">
  <img alt="OpenWrt" src="https://img.shields.io/badge/OpenWrt-22D3EE?style=flat-square&logo=openwrt&logoColor=05070D&labelColor=0D1320">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-22D3EE?style=flat-square&logo=linux&logoColor=05070D&labelColor=0D1320">
  <img alt="Git" src="https://img.shields.io/badge/Git-22D3EE?style=flat-square&logo=git&logoColor=05070D&labelColor=0D1320">
</p>

## · ✦ · Беру заказы

Telegram-боты · Android-приложения · веб-панели и сайты. Как работаю: **бриф** → **план и сроки** → **разработка с промежуточными демо** → **передача с инструкциями и поддержкой**.

<img alt="Открыт к проектам" src="https://img.shields.io/badge/СЕЙЧАС-Открыт%20к%202–3%20проектам%20в%20месяц-F59E0B?style=flat-square&labelColor=0D1320">

## · ✦ · English

**Dmitry Damianov** — engineer behind Unclavix, a closed P2P messenger in Rust. Also available for Telegram bots, Android apps and web panels.
Rust · Kotlin · Go · OpenWrt · Linux.

<p align="center"><a href="https://t.me/imbazyx"><b>Написать в Telegram →</b></a></p>

<sub>Unclavix разрабатывается в исследовательских целях.</sub>
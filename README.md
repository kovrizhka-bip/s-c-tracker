# s-c-tracker


![S&C-Tracker](assets/logo.jpeg)

# S&C-Tracker — Multi-market data aggregator for traders and investors

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/yourusername/snc-tracker/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)]()

**60+ liquidity sources. Stocks, crypto, derivatives. Real-time data, precision accuracy, institutional-grade reliability.**

---

## 📌 Why S&C-Tracker?

S&C-Tracker was born from the chaos of fragmented data streams — named by traders who demand precision, speed, and absolute reliability.

- **S&C** stands for **Stocks & Crypto** — the two dominant asset classes in today's market.
- **Tracker** keeps your finger on the pulse — your unified command center.

Under the hood, WASM kernels written in Rust power the aggregation engine, anomaly detection, and cross-market correlation system.

- **15,000+** market pairs
- **24/7/365** real-time monitoring
- **Sub-second** data updates

This is not just another dashboard.

---

## 🚀 Features

| Feature | Description |
|---------|-------------|
| **Real-time price tracking** | Live updates for stocks, cryptocurrencies, and derivatives |
| **Multi-source aggregation** | Data from 60+ liquidity sources and exchanges |
| **Cross-market correlation** | Identify trends across different asset classes |
| **Custom watchlists** | Create and manage personalized portfolios |
| **Price alerts** | Get notified when assets hit your target levels |
| **Historical data** | Access charts and historical price movements |
| **No AI, no magic** | Just accurate, reliable data when you need it |

---

## 📊 Supported Markets

### Stocks
- US equities (NYSE, NASDAQ)
- European markets
- Asian markets

### Cryptocurrencies
- Bitcoin (BTC), Ethereum (ETH), and 200+ altcoins
- Major exchanges: Binance, Coinbase, Kraken, Bybit

### Derivatives
- Futures
- Options
- Perpetual swaps

---

## 🛠️ Tech Stack

- **Core engine:** Rust with WASM
- **Frontend:** [Your frontend stack, e.g., Tauri / Electron / React]
- **Data aggregation:** Custom Rust-based pipeline
- **Real-time updates:** WebSockets

---

## 📦 Installation

### Prerequisites
- [Your requirements, e.g., Node.js 18+, Rust 1.70+]

### From source
```bash
git clone https://github.com/yourusername/snc-tracker.git
cd snc-tracker
# Add build instructions here

## User story
>**Как держатель акций и/или криптовалют, я хочу видеть на одной странице одновременно и акции и криптовалюты и изменение их стоимости, что очень сильно упрощает процесс отслеживания своего портфеля.**
>
>Критерии:
+ отображение графика изменения стоимости портфеля
+ вывод перечня акций и их стоимости
+ красивый и удобный интерфейс полностью на русском языке

## Use case
>Название: **Добавление акционного портфеля**
>
>Акторы: Пользователь, Система, сайт
>
>Предусловия:
+ пользователь авторизован;
+ пользователь выбрал актив/активы для отслеживания
  
>Основной поток:
1. Пользователь нажимает на кнопку “добавить актив”
2. Система отображает окно выбора активов
3. Пользователь ищет в окне нужный актив
4. Найдя нужный актив, он на него нажимает
5. Система отображает новое окно добавления активов
6. В этом окне пользователь вводит количество актива и его стоимость на момент покупки
7. Пользователь нажимает кнопку “добавить актив”
8. Система переносит пользователя на страницу его портфеля и отображает изменения
   
>Альтернативные потоки:
>>А1: Пользователь не находит нужный актив в списке → звонит на мой телефон и просит добавить его актив
>>
>>А2: Пользователь не корректно вводит данные (отрицательная стоимость актива и вводит не численные значения) → кнопка “добавить актив” не работает

>Постусловия:
+ задача решена или пользователь позвонит на горячую линию и придется чуточку подождать (не более одного часа)
+ прогресс пользователя обновлён в системе

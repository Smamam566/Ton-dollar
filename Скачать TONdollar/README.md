
# TON$ Jetton Project

## ✅ Как запустить через GitHub Codespaces
1. Создай репозиторий на GitHub (назови TON-dollar).
2. Загрузи все файлы из этого архива.
3. Нажми **Code → Open with Codespaces → New codespace**.
4. Подожди автоустановки (1–2 минуты).

### 📌 Сборка контракта:
```
toncli build
```

### 📌 Деплой в testnet:
```
toncli deploy --network testnet
```

### 📌 Получи тестовые TON:
https://faucet.ton.org

### 📌 Минт токенов:
```
toncli run contracts/jetton-minter.fc mint <your_wallet_address> 1000
```

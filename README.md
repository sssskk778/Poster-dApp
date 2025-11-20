
# Poster dApp - Гостевая книга в блокчейне

Простое приложение для для создания постов в блокчейн Ethereum.

## Что внутри

- `poster-contract/` - смарт-контракты на Hardhat
- `poster-ui/` - веб-интерфейс на Next.js

## Как запустить

**Контракты:**
```bash
cd poster-contract
npm install
npx hardhat compile
```

**Фронтенд:**
```bash
cd poster-ui
npm install
npm run dev
```

## Функции

- Подключение MetaMask
- Отправка сообщений в блокчейн
- Просмотр всех записей
- Фильтрация по тегам

## Технологии

- Solidity, Hardhat
- Next.js, Web3.js
- Sepolia testnet
  
## Contract Address

0x... - Deployed on Sepolia testnet

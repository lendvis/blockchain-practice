# Блокчейн-практика студии Лендвис

**Витрина: https://olegg000.github.io/blockchain-practice/**

Страница-обзор блокчейн-направления: четыре сети, в которых студия писала смарт-контракты
и чейнкод, что из этого лежит в открытом доступе и почему остальное закрыто соглашением
с заказчиком.

## Сети и открытый код

| Сеть | Язык | Открытый код |
|------|------|--------------|
| TON | FunC | Jetton-минтер TEP-74 с он-чейн вестингом — работа закрыта соглашением с заказчиком |
| Hyperledger Fabric | TypeScript | [fabric-supply-chain-ts](https://github.com/Olegg000/fabric-supply-chain-ts) — чейнкод учёта поставок, 14 тестов |
| Waves Enterprise | TypeScript | [waves-enterprise-integration](https://github.com/Olegg000/waves-enterprise-integration) — токенизация документов по SHA-256, 9 тестов |
| Ethereum | Solidity | в открытый доступ не выкладывался |

## Как устроена страница

Один самодостаточный `docs/index.html`: разметка, стили и скрипты внутри, из внешнего —
только веб-шрифты. Карта сетей нарисована inline-SVG и перестраивается под ширину экрана,
узлы выбираются мышью, тапом и с клавиатуры. Публикуется через GitHub Pages из папки `docs/`.

```
open docs/index.html
```

---

Студия Лендвис · [olegg000.github.io/lendvis](https://olegg000.github.io/lendvis/)

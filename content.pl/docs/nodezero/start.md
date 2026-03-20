---
weight: 1
title: "NodeZero — kiedy sieć publiczna przestaje być opcją"
date: 2026-03-11
tags: ["nodezero", "energia", "offgrid"]
---
weight: 1

NodeZero zaczął się od awarii. Cztery godziny bez prądu, zamrożona praca, utracone dane. Standardowa odpowiedź to UPS — system podtrzymania przez kilka minut. Ale co jeśli awaria trwa cztery dni?

## Założenie projektu

NodeZero to nie backup. To infrastruktura energetyczna zdolna do działania w pełnej izolacji od sieci publicznej. Cel: 72-godzinna autonomia bez utraty funkcjonalności.

Stack:
- **UPS** — 48V LiFePO4, 20kWh pojemność użytkowa
- **GENSET** — dieselowy agregat jako backup dla UPS
- **GASIFIER** — zgazowarka węgla drzewnego jako backup dla genset

Każda warstwa może zastąpić poprzednią. Trzy poziomy redundancji.

## Dlaczego zgazowanie?

Diesel ma jeden problem: zależność od sieci dystrybucji paliwa. W scenariuszu poważnej awarii infrastruktury — nie będzie dostaw. Zgazowarka działa na biomasie, węglu lub odpadach drzewnych. Paliwo można produkować lokalnie.

To nie romantyzm off-grid. To inżynierskie myślenie o odporności systemów.

## Status projektu

Aktualnie: UPS działa stabilnie od 8 miesięcy. GENSET — testy integracji z automatycznym przełączaniem. GASIFIER — faza badawcza, dokumentacja pod: [nodezero.enklava.co](https://nodezero.enklava.co)

Kolejny wpis: jak zbudować moduł EGR dla zgazowarki klasy 5kW.

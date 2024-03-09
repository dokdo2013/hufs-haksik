# HUFS Haksik

한국외국어대학교 학식 조회 SDK & API

Hankuk University of Foreign Studies Cafeteria API & SDK

## Getting Started

`hufs-haksik` 은 한국외국어대학교 학식 조회 SDK & API 입니다.

### Installation

```bash
npm install hufs-haksik
```

### Simple Usage

```typescript
import { getHaksik, getRestaurant } from "hufs-haksik";

// Get restaurant list
const restaurants = getRestaurant();

// Get restuarant information from restaurant name
const restaurant = getRestaurant("인문관식당");

// Get today's haksik menu from all restaurants
const haksik = getHaksik();

// Get today's haksik menu from specific restaurant
const haksik = getHaksik({
  restaurant: "인문관식당",
});

// Get today's haksik menu from specific restaurant and meal

// Get haksik menu from specific date
const haksik = getHaksik({
  date: "2024-04-01",
});

// Get haksik menu from specific date and restaurant
const haksik = getHaksik({
  date: "2024-04-01",
  restaurant: "인문관식당",
});

// Get haksik menu from date range
const haksik = getHaksik({
  startDate: "2024-04-01",
  endDate: "2024-04-30",
});
```

## 프로젝트 구성

- Language : Typescript
- Monorepo : Pnpm workspace & Turborepo

- SDK : `/apps/hufs-haksik`
- API : `/apps/api`
- Documents : `/apps/docs`

## SDK 사용법

## API 사용법

```

```

## Credit

Made with ❤️ by [@dokdo2013](https://github.com/dokdo2013) (HUFS 교육대학원 컴퓨터교육전공 조현우)

---
title: Introduction
description: Introduction to NgRx Slice
layout: ../../layouts/MainLayout.astro
---

`ngrx-slice` is a plugin that intends to provide the same functionalities that [ReduxToolkit createSlice](https://redux-toolkit.js.org/api/createSlice) provides. It is meant to be **opinionated**

`ngrx-slice` assumes the consumers' knowledge of [NgRx](https://ngrx.io)

### Features

- ✅ Express a slice of the global state in a central place
- ✅ Generate `ActionCreators` from reducers' cases
- ✅ Generate **Async** `ActionCreators` from reducers' cases
- ✅ Generate `MemoizedSelectors` from `initialState`
- ✅ Utilize `immer` and `ngrx-immer` under the hood for State updates
- ✅ Customizable Actions' types

### Peer Dependencies

| NgRx Slice | Angular | NgRx   |
| ---------- | ------- | ------ |
|            |         |        |
| v6         | v13,14  | v13,14 |
| v5         | v11,12  | v11,12 |

> No support for Angular < 11 because of TypeScript version

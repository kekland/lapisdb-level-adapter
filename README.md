# lapisdb-level-adapter

A [*LevelDB*](https://github.com/level/level) adapter for [**LapisDB**](https://github.com/kekland/lapisdb).

## Installation

```bash
npm i --save lapisdb-level-adapter
```

## Usage

```ts
import { LevelDbAdapter } from 'lapisdb-level-adapter'
import { MyModel } from './model'

const databaseName = 'test'
const directory = './database'

const adapter = new LevelDbAdapter(MyModel, {name: databaseName, directory: directory})

const datastore = new Datastore<Planet>('test', adapter)
```

For more information see [LapisDB documentation](https://github.com/kekland/lapisdb).

## 📧 Contact me

**E-Mail**: `kk.erzhan@gmail.com`

---
title: node.ts
nav_order: 5
parent: "@sqlfx/sqlite"
---

## node overview

Added in v1.0.0

---

<h2 class="text-delta">Table of contents</h2>

- [constructor](#constructor)
  - [make](#make)
  - [makeCompiler](#makecompiler)
  - [makeLayer](#makelayer)
- [models](#models)
  - [SqliteClient](#sqliteclient)
- [tags](#tags)
  - [tag](#tag)
- [utils](#utils)
  - [transform](#transform)

---

# constructor

## make

**Signature**

```ts
export declare const make: (options: SqliteClientConfig) => Effect.Effect<Scope, never, SqliteClient>
```

Added in v1.0.0

## makeCompiler

**Signature**

```ts
export declare const makeCompiler: (transform?: ((_: string) => string) | undefined) => Statement.Compiler
```

Added in v1.0.0

## makeLayer

**Signature**

```ts
export declare const makeLayer: (
  config: Config.Config.Wrap<SqliteClientConfig>
) => Layer.Layer<never, ConfigError, SqliteClient>
```

Added in v1.0.0

# models

## SqliteClient

**Signature**

```ts
export declare const SqliteClient: any
```

Added in v1.0.0

# tags

## tag

**Signature**

```ts
export declare const tag: Tag<SqliteClient, SqliteClient>
```

Added in v1.0.0

# utils

## transform

Column renaming helpers.

**Signature**

```ts
export declare const transform: typeof import('/Volumes/Code/sqlfx/packages/sql/src/Transform')
```

Added in v1.0.0
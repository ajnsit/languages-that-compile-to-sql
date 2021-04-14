# Languages That Compile to SQL
A curated list of languages that compile to, or generate, SQL

## Table of contents

- [Strongly Typed](#strongly-typed)
- [Visual Programming](#visual-programming)
- [Alternate Query Syntax](#alternate-query-syntax)
- [Logic Programming](#logic-programming)
- [Language DSLs](#language-dsls)
- [ORMs](#orms)
- [SQL Extensions](#sql-extensions)
- [Ideas/Proposals](#ideasproposals)
- [Others](#others)

## Strongly Typed

| Name | Description | Source |
| :---- | :---- | :---- |
| [Ermine](https://ermine-language.github.io/) | Lazy, Pure, with Strong Static Types. It's Haskell-like Functional Programming Language that adds support for Row Types. Compiles to SQL queries. | https://github.com/ermine-language/ |

## Alternate Query Syntax

| Name | Description | Source |
| :---- | :---- | :---- |
| [GraphQL](https://graphql.org/) | Schema description, query, and manipulation langauge, well suited for web services. There's an implementation available that compiles GraphQL to Postgres SQL queries ([Hasura GraphQL Engine](https://github.com/hasura/graphql-engine)). | https://github.com/hasura/graphql-engine |

## Logic Programming

| Name | Description | Source |
| :---- | :---- | :---- |
| [Datalog](https://en.wikipedia.org/wiki/Datalog) | Declarative and non-turing complete subset of prolog, which can be used to query relational databases. Query evaluation with Datalog is based on first order logic and is sound and complete. Datalog programs can be translated to **recursive SQL** queries (part of the SQL:1999 standard). | https://github.com/ekoontz/psqlog (Any others?) |
| [Yedalog](https://research.google/pubs/pub43462/) | A logic programming language from Google that compiles to SQL | NONE |
| [Logica](https://logica.dev/) | Successor to Yedalog, and inspired by Datalog, it's an open source logic programming language from Google. It compiles to SQL which can run on Google BigQuery, and has experimental support for PostgreSQL and SQLite | https://github.com/EvgSkv/logica |

## Language DSLs

TODO

## Visual Programming

TODO

## ORMs

TODO

## SQL Extensions

TODO

## Ideas/Proposals

TODO

## Others

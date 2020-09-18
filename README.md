# Languages That Compile to SQL
A curated list of languages that compile to, or generate, SQL

## Table of contents

- [Strongly Typed](#strongly-typed)
- [Visual Programming](#visual-programming)
- [Alternate Query Syntax](#alternate-query-syntax)
- [Language DSLs](#language-dsls)
- [ORMs](#orms)
- [SQL Extensions](#sql-extensions)
- [Ideas/Proposals](#ideasproposals)
- [Others](#others)

## Strongly Typed

| Name | Description |
| :---- | :---- |
| [Ermine](https://ermine-language.github.io/) | Lazy, Pure, with Strong Static Types. It's Haskell-like Functional Programming Language that adds support for Row Types. Compiles to SQL queries. |

## Alternate Query Syntax

| Name | Description |
| :---- | :---- |
| [GraphQL](https://graphql.org/) | Schema description, query, and manipulation langauge, well suited for web services. There's an implementation available that compiles GraphQL to Postgres SQL queries ([Hasura GraphQL Engine](https://github.com/hasura/graphql-engine)). |
| [Datalog](https://en.wikipedia.org/wiki/Datalog) | Declarative and non-turing complete subset of prolog, which can be used to query relational databases. Query evaluation with Datalog is based on first order logic and is sound and complete. Allows recursive queries. Some widely used database systems include ideas and algorithms developed for Datalog. For example, the SQL:1999 standard includes recursive queries, and the Magic Sets algorithm (initially developed for the faster evaluation of Datalog queries) is implemented in IBM's DB2.

Datalog programs can be translated to **recursive SQL** queries. The problem of deciding whether for a given Datalog program there is an equivalent nonrecursive program (corresponding to a positive relational algebra query, or, equivalently, a formula of positive existential first-order logic, or, as a special case, a conjunctive query) is known as the **Datalog boundedness problem** and is **undecidable**.

|

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

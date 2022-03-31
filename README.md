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
- [Misc](#misc)

## Strongly Typed

| Name | Description | Source |
| :---- | :---- | :---- |
| [Ermine](https://ermine-language.github.io/) | Lazy, Pure, with Strong Static Types. It's Haskell-like Functional Programming Language that adds support for Row Types. Compiles to SQL queries. | https://github.com/ermine-language/ |

## Alternate Query Syntax

| Name | Description | Source |
| :---- | :---- | :---- |
| [GraphQL](https://graphql.org/) | Schema description, query, and manipulation langauge, well suited for web services. There's an implementation available that compiles GraphQL to Postgres SQL queries ([Hasura GraphQL Engine](https://github.com/hasura/graphql-engine)). | https://github.com/hasura/graphql-engine |
| [LINQ](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/) | LINQ is a declarative and typed query syntax that adds query capabilities to C#. Atleast one [standalone LINQ to SQL translator](https://github.com/ethanli83/EFSqlTranslator) written in C# is available as open source. | https://github.com/ethanli83/EFSqlTranslator |


## Logic Programming

| Name | Description | Source |
| :---- | :---- | :---- |
| [Datalog](https://en.wikipedia.org/wiki/Datalog) | Declarative and non-turing complete subset of prolog, which can be used to query relational databases. Query evaluation with Datalog is based on first order logic and is sound and complete. Datalog programs can be translated to **recursive SQL** queries (part of the SQL:1999 standard). | https://github.com/ekoontz/psqlog (Any others?) |
| [Yedalog](https://research.google/pubs/pub43462/) | A logic programming language from Google that compiles to SQL | NONE |
| [Logica](https://logica.dev/) | Successor to Yedalog, and inspired by Datalog, it's an open source logic programming language from Google. It compiles to SQL which can run on Google BigQuery, and has experimental support for PostgreSQL and SQLite | https://github.com/EvgSkv/logica |
| [Constraint Handling Rules (CHR)](https://en.wikipedia.org/wiki/Constraint_Handling_Rules) | A declarative, rule-based programming language. Although CHR is Turing complete, it is not commonly used as a programming language in its own right. Rather, it is used to extend a host language with constraints. Prolog is by far the most popular host language and CHR is included in several Prolog implementations, including SICStus and SWI-Prolog, although CHR implementations also exist for Haskell, Java, C, SQL, and JavaScript. There is a [CHR2 to SQL converter](https://github.com/awto/chr2sql) available | https://github.com/awto/chr2sql |


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

## Misc

1. Advent of code 2021 solved with SQL queries. [Code](https://github.com/mitchellh/advent-2021-sql), [Video explanations for each day](https://youtube.com/playlist?list=PL4z1WbdlT5GJqdGnuvoqw4dOdB2etJ6sd).

---
id: flow-operations
title: Flow Operations
---

The `@graphql-codegen/flow-operations` plugin generates Flow types based on your `GraphQLSchema` and your GraphQL operations and fragments.

It generates types for your GraphQL documents: Query, Mutation, Subscription and Fragment.

This plugin requires you to use `@graphql-codegen/flow` as well, because it depends on it's types.

{@import ../plugins/client-note.md}

## Installation

    $ yarn add -D @graphql-codegen/flow-operations

## Configuration

{@import ../generated-config/base-visitor.md}

{@import ../generated-config/base-documents-visitor.md}

{@import ../generated-config/flow-operations.md}

---
sidebar_label: "Part III: Automatic CRUD API"
sidebar_position: 3
---

# Part III: Automatic CRUD API

In Part I, we learned how ZenStack extended Prisma ORM on the schema and runtime levels. By making these extensions, ZenStack unleashed many new potentials of the ORM and turned it into a data access layer that enforces access control and additional data integrity.

One interesting side effect of this extension is that we can automatically derive CRUD APIs from the schema. The data models tell us how the input/output of the APIs should look like, and the enhanced Prisma Client ensures that the APIs are secure.

In this part of the guide, we'll learn how such automatic APIs work - the general architecture, the different flavors of APIs, and how they integrate into the framework of your choice.

We'll also continue evolving our Todo project into a fully functional backend service. If you're unfamiliar with the project, please first revisit the [Sample Project](/docs/the-complete-guide/#sample-project) part. You can use the "part2" branch of [the-complete-guide-sample](https://github.com/zenstackhq/the-complete-guide-sample/tree/part2) as a starting point.

Let's get started.

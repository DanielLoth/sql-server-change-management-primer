# The SQL Server change management primer

## Motivation

* Learn how to work effectively with SQL Server databases, particularly with respect to minimising downtime while managing change.
* Learn how to use tools like `sqlpackage.exe` to effect that change.

## Contributing

Contributions are welcome.

Please raise pull requests for the following:
* Fixing errors (typographical and similar)
* Technical errata within existing content.

Please start a discussion first for the following:
* Whole new sections of content
  * The discussion is mostly to ensure fit within the broader primer, and to ensure that you aren't wasting time working on something that might already be in progress.

## Index of topics

* [The sqlpackage tool](#the-sqlpackage-tool)
  * [Complexities in sqlpackage](#complexities-in-sqlpackage)
* [Manually changing data](#manually-changing-data)


## The sqlpackage tool

> The sqlpackage.exe tool is best described as a desired state management tool.
>
> It allows you to prescribe what the database *should* look like (i.e., the desired state) and - where discrepancies exist - the tool generates the necessary T-SQL queries to get the database into that desired state.

### Complexities in sqlpackage

## Manually changing data

> Sometimes you might to effect manual change. That is, a change executed by a human manually as opposed to a change executed within the context of your deployment pipeline.
>
> This is hopefully a rare occurrence. But for some businesses it's perhaps not rare at all.

### Changing small volumes of data

### Changing large volumes of data

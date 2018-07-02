# dbt SQL Grammar for VS Code [![VS Code marketplace button](https://vsmarketplacebadge.apphb.com/installs/joshpeng.dbt-sql.svg)](https://marketplace.visualstudio.com/items?itemName=joshpeng.dbt-sql)
![dbt_](https://raw.githubusercontent.com/joshpeng/dbt-sql/master/images/dbt_.png)

[dbt_](https://www.getdbt.com/) is a powerful CLI tool that helps data analysts/scientists/engineers transform data in their data warehouse. To do this, it uses Python's templating engine, [Jinja](http://jinja.pocoo.org/), inside your SQL files.

This extension provides syntax highlighting support of the Jinja statements and expressions inside the SQL that **dbt_** uses. It needs to be used in conjunction with a color theme that supports the Jinja scope.


## Installation

1. Install dbt_ SQL via `ext install dbt-sql` in Command Palette
2. When opening a `.sql` file, ensure the language mode is set to `SQL (dbt)`


## Suggested Color Theme

For best results, please consider using the `One Dark+ (Sublime)` themes from [here](https://marketplace.visualstudio.com/items?itemName=joshpeng.theme-onedark-sublime).
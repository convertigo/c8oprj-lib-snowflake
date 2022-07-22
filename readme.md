


# lib_Snowflake

This is the SnowFlake connector for Convertigo low Code platform. The connector uses the SnowFlake JDBC driver to execute SQl queries on the cloud databases.

## Symbols

Some symbols must be defined to use this connector

|Symbol     | Usage                 |
|------------|----------------------|
| lib_snowflake.endpoint | The Snowflake end point. This is found in the URL to access your account after the 'https://' |
| lib_snowflake.user | Your SnowFlake user name when you created your snowflake account |
| lib_snowflake.password.secret | Your SnowFlake password when you created the SnowFlake account |




For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Sequences](#sequences)
    - [ExecuteQuery](#executequery)


## Installation

1. In your Convertigo Studio use `File->Import->Convertigo->Convertigo Project` and hit the `Next` button
2. In the dialog `Project remote URL` field, paste the text below:
   <table>
     <tr><td>Usage</td><td>Click the copy button</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_Snowflake=https://github.com/convertigo/c8oprj-lib-snowflake.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_Snowflake=https://github.com/convertigo/c8oprj-lib-snowflake/archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_Snowflake__ project


## Sequences

### ExecuteQuery

Executes a Query on SnowFlake. The query must be in SQL format and you must provide the schema and the query itself


**variables**

<table
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>Query</td><td></td>
</tr>
<tr>
<td>Schema</td><td></td>
</tr>
</table>



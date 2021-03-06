# Changelog

## 1.2.0
- Add `DdlParseTable.to_bigquery_ddl` function.
    - BigQuery DDL (CREATE TABLE) statement generate function.
- Add `DdlParseColumn.bigquery_legacy_data_type` property.
    - Get BigQuery Legacy SQL data property.
    - Alias of `DdlParseColumn.bigquery_data_type` property.
- Add `DdlParseColumn.bigquery_standard_data_type` property.
    - Get BigQuery Standard SQL data property.

## 1.1.3
- Add support inline comment.
- Add support constraint name with quotes.
- Add support Oracle Length Semantics for Character Datatypes.

## 1.1.2
- Add support Oracle data type.
    - `CLOB`, `NCLOB`
    - `NUMBER` with no length & scale specification
- Miner fix.

## 1.1.1
- Fix Postgres/Redshift parse of "::" syntax in field attribute.

## 1.1.0
- Add `source_database` option.
- Add `to_bigquery_fields` method to Columns dicttionary(`DdlParseColumnDict` class).
- Fix BigQuery convert of Oracle data type.
    - Oracle 'DATE' -> BigQuery 'DATETIME'
    - Oracle 'NUMBER' -> BigQuery 'INTEGER' or 'FLOAT'

## 1.0.2
- Miner enhancement.
    - `ddlparse.py` : Exclude unused module.
    - `example.py` : Modified comment.
    - `README.md` : Miner fix.

## 1.0.1
- Miner enhancement.

## 1.0.0
- Initial released.

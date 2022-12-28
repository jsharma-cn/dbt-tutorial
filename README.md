# dbt-tutorial

dbt run --full-refresh

dbt test --select stg_customers

Execute dbt test to run all generic and singular tests in your project.
Execute dbt test --select test_type:generic to run only generic tests in your project.
Execute dbt test --select test_type:singular to run only singular tests in your project.

Source test case testing

dbt test --select source:jaffle_shop

Source freshness:
dbt source freshness


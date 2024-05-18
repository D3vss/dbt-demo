# dbt-demo

This repo acts as a demo for the capabilities of dbt.

# What is dbt?
# Folder structure explanation:

- analyses:
- dbt_packages:
- logs:
- macros:
- models:
- seeds: place static files here (csv files,...).
- snapshots:
- tests: https://docs.getdbt.com/docs/build/data-tests

# dbt_project.yml:

# packages.yml:
You can add packages and dependencies in this file to be installed using dbt deps.
We installed this package https://hub.getdbt.com/dbt-labs/dbt_utils/latest/ that contains reusable macros.

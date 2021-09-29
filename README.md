# DBT Analysis

This is a base project to check different ways to [work with more than two projects](https://discourse.getdbt.com/t/how-to-configure-your-dbt-repository-one-or-many/2121).

## Building the project

The easy way to work with the project is use the `./dbt` script. This script use the dbt local installation if is installed, or the dbt Docker container image, if not installed. So, for example, to check the version you will use: `./dbt --version`.

### Basic commands

```bash
# Clean the project
./dbt clean

# Compile the project
./dbt compile

# Generate and serve the documentation:
./dbt docs generate && ./dbt docs serve

# Run the project
./dbt run

# Test the project
./dbt run
```

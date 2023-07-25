# RollingDuckDB.jl
__Add Julia to DuckDB [rollfun benchmarks](https://github.com/duckdblabs/db-benchmark/pull/9).__

### Approach

- using (all)
  - DuckDB.jl
  - DataTables.jl
  - RollingFunctions.jl
  - VectorizedStatistics.jl
- provide test data (select)
  - generate our own test data
  - copy db-benchmark generated test data
  - duplicate db-benchmark test data generation
- keep test data (select)
  - in memory
  - in .csv files
  - in DuckDB files

### High Level Design Notes

- ...
  

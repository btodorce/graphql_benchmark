Fork of graphql-bench

1. install the node_modules inside app & queries
2. cd app
3. yarn [any of the benchmark scripts inside package.json]
4. When running outside of a docker container
`run binary at app/cli/bin by running chmod +x run
k6 binary at app/queries/bin/k6/ by running chmod +x k6
wrk binary at app/queries/bin/wrk/ by running chmod +x wrk`

Fork of graphql-bench

1. install the node_modules inside app & queries
2. cd app
3. yarn [any of the benchmark scripts inside package.json]
4. Inside cd/queries/config, adjust the jwt header
5. Next steps are when running it outside of a docker container
6. run binary at app/cli/bin by running chmod +x run
7. k6 binary at app/queries/bin/k6/ by running chmod +x k6
8. wrk binary at app/queries/bin/wrk/ by running chmod +x wrk

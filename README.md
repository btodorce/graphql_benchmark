Fork of graphql-bench

1. cd app
2. install the node_modules inside app, queries and cli
3. Inside cd/queries/config, adjust the jwt header
4. run binary at app/cli/bin by running chmod +x run
5. k6 binary at app/queries/bin/k6/ by running chmod +x k6
6. wrk binary at app/queries/bin/wrk/ by running chmod +x wrk
7. yarn [any of the benchmark scripts inside package.json]

Once the testing has finished
1. Open, app/web-app/index.html in your browser6
2. Load the testing results from app/queries/reports

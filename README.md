# postgreSQL-arm64-cube350
Docker build of postgresql-arm64-9.6 changing the dimension limit for the cube extension, raising it to 350
postgresql-arm64-9.6的Docker构建更改了多维数据集扩展的维度限制，将其提高到350
## common problem(常见问题)
构建如提示#!/usr/bin/env bash错误，请百度::set ff

Build prompt error #!/usr/bin/env bash , Please search ::set ff

## Build command (构建命令)
``sh
docker build -t postgresql-large-cube:9.6 .
``

# test-swagger

[doc](https://michiokakiuchi.github.io/test-swagger/dist/index.html)


## パターン１
npm install -g @apidevtools/swagger-cli

cd ./docs/swagger
swagger-cli bundle -t yaml ./index.yaml -o ../swagger.yaml
⇒これダメｗ

## パターン２
npm install -g multi-file-swagger
cd ./docs/swagger
multi-file-swagger -o yaml ./index.yaml > ../swagger.yaml

⇒ほんとに、ファイルが結合されるだけ、、できれば、プロパティのチェックとかもやってほしいかも。


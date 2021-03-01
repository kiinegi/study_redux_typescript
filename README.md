# study_redux_typescript
ReactのReduxを学ぶためにDocker-composeで環境を作ってgithubで管理するもの

備忘録
Dockerfile、Docker-compose.ymlからコンテナを立ち上げる

①docker-compose build

②docker-compose run　実行コマンド
docker-compose run --rm redux-typescript sh -c 'npx create-react-app redux-typescript  --template redux-typescript'

③docker-compose up
デタッチする方が楽

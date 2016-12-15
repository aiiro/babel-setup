# Babel Setup

モジュールをインストール
```
yarn init
yarn add babel-cli --dev
yarn add babel-preset-env --dev
```

.babelrcを作成
```
echo '{ "presets": ["env"] }' > .babelrc
```

トランスパイル
```
yarn run build
```
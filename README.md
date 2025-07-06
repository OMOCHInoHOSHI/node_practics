# node_practics


## 環境構築


### コアマンドライン
``` cl
node-v
```
v24.3.0

``` cl
npm init -y
```

``` cl
npm install typescript @types/node -D
```

### tsconfig.json
```
{
  "compilerOptions": {
    // コンパイル後のJavaScriptのバージョン
    "target": "ESNext",
    // モジュールシステム
    "module": "NodeNext",
    // .ts拡張子を持つファイルのインポートを可能に
    "allowImportingTsExtensions": true,
    // モジュール解決の際に、TypeScriptの構文を厳密に解釈
    "verbatimModuleSyntax": true,
    // すべての厳格な型チェックオプションを有効に
    "strict": true
  }
}
```

### package.jsonファイル修正

```
"scripts": {
    "typecheck": "tsc --noEmit"
  },
```


## 参考
https://ics.media/entry/4682/

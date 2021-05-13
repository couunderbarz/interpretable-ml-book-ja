# Developer Guide
## Issue について

誤訳を発見した際は、 issue の作成を行ってください。
複数箇所誤訳を発見された場合でも、issue は章 (1.1, 1.2 など) ごとに作成してください。

issue の内容としては、以下を明記してください。

* 章番号
* 誤訳箇所
* 正しい訳

## Pull Request について

web で公開されている和訳のバージョンは、`japanese` ブランチになっています。
Pull Request を作る場合は、`japanese` ブランチから、`issue/#{issue番号}/{名前}` という命名規則でブランチを切って作業を行い、Push した後、Pull Request を作成してください。
ただし、Pull Request は `master` ブランチではなく、 `japanese` ブランチに対して送るようにしてください。

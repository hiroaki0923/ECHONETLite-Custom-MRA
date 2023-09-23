# ECHONETLite Custom MRA

[ECHONETLite2MQTT](https://github.com/banban525/echonetlite2mqtt)を利用し、快適エアリーやニチコンの蓄電池の拡張プロパティを扱えるようにするためのカスタムMRA。

- 0x0130.json
  - 快適エアリーが制御する3つのゾーンの室温・風量・設定温度などを取得する
- 0x027D.json
  - ニチコン蓄電池のリモコンが制御する充放電時間情報を取得する



上記のMRAは[ECHONETコンソーシアムで配布されているもの](https://echonet.jp/spec_mra/)を改変したものです。

現行の記述では、ECHONETLite2MQTTにおいて同じオブジェクトコードのメッセージ全てにこの変更が適用されるため、上記以外の同一オブジェクトコードの機材がネットワーク上に存在する場合には不具合が起こる可能性があります。

自己責任でご利用ください。

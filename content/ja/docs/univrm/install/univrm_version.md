---
title: "UniVRM Version"
tags: ["unity"]
---

# Version

* 更新で入った新しいバグ: バージョンアップで新規に混入したバグ。迅速にバグフィックス

| date     | version                                                                                                                          | 更新で入った新しいバグ      | 更新内容・備考                                                               |
|----------|----------------------------------------------------------------------------------------------------------------------------------|-----------------------------|------------------------------------------------------------------------------|
| 2019     | [0.55.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.55.0)                                                                    |                             | Unity-5.6 対応最終版                                                         |
| 2020     | [0.56.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.56.0)                                                                    | x                           | Unity-2018.4 に変更                                                          |
|          | [0.56.1](http://github.com/vrm-c/UniVRM/releases/tag/v0.56.1)                                                                    | x                           |                                                                              |
|          | [0.56.2](http://github.com/vrm-c/UniVRM/releases/tag/v0.56.2)                                                                    | x                           |                                                                              |
|          | [0.56.3](http://github.com/vrm-c/UniVRM/releases/tag/v0.56.3)                                                                    |                             |                                                                              |
|          | [0.57.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.57.0)                                                                    |                             | ボーン名重複時にに自動でリネームするようになりました                         |
|          | [0.57.1](http://github.com/vrm-c/UniVRM/releases/tag/v0.57.1)                                                                    |                             |                                                                              |
|          | [0.58.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.58.0)                                                                    | [^firstperson_import]       | エクスポートダイアログの作り直し                                             |
|          | [0.58.1](http://github.com/vrm-c/UniVRM/releases/tag/v0.58.1)                                                                    |                             |                                                                              |
|          | [0.59.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.59.0)                                                                    |                             | springBone の Missing を検知してメッセージ                                   |
|          | [0.60.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.60.0)                                                                    |                             | null check 的なものが増えて、モデル改変してもエラーが出にくくなりました      |
|          | [0.61.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.61.0) [milestone](https://github.com/vrm-c/UniVRM/milestone/20?closed=1) | [^springcollider]           | UniUnlit の頂点カラー。AOT問題を修正                                         |
|          | [0.61.1](http://github.com/vrm-c/UniVRM/releases/tag/v0.61.1)                                                                    |                             |                                                                              |
|          | [0.62.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.62.0) [milestone](https://github.com/vrm-c/UniVRM/milestone/21?closed=1) |                             | BlendShape bake の動作が正しくなった                                         |
| 2021     | [0.63.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.63.0) [milestone](https://github.com/vrm-c/UniVRM/milestone/25?closed=1) | [^jpg] [^keywordmap] [^upm] | jpg問題あり。UniGLTF分離                                                     |
|          | [0.63.1](http://github.com/vrm-c/UniVRM/releases/tag/v0.63.1)                                                                    | [^jpg] [^keywordmap]        | jpg問題あり                                                                  |
|          | [0.63.2](http://github.com/vrm-c/UniVRM/releases/tag/v0.63.2)                                                                    |                             |                                                                              |
|          | [0.64.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.64.0) [milestone](https://github.com/vrm-c/UniVRM/milestone/23?closed=1) | [^asmdef]                   | メッシュの一部を削除したときのエクスポートエラーを回避。vrm-1.0 Experimental |
|          | [0.65.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.65.0)                                                                    | [^build]                    |                                                                              |
|          | [0.65.1](http://github.com/vrm-c/UniVRM/releases/tag/v0.65.1) [misestone](https://github.com/vrm-c/UniVRM/milestone/28?closed=1) | [^build]                    | トルコ語のExportを修正[\#696](https://github.com/vrm-c/UniVRM/issues/696)    |
|          | [0.65.2](http://github.com/vrm-c/UniVRM/releases/tag/v0.65.2) [milestone](https://github.com/vrm-c/UniVRM/milestone/29?closed=1) |                             |                                                                              |
|          | [0.65.3](http://github.com/vrm-c/UniVRM/releases/tag/v0.65.3)                                                                    |                             | UniGLTFのバージョン。UPM専用。パッケージリリース無し                         |
|          | [0.66.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.66.0) [milestone](https://github.com/vrm-c/UniVRM/milestone/26?closed=1) |                             | 未正規化ヒエラルキーにスプリングボーンがあるときの警告メッセージ             |
| 2/10予定 | [0.67.0](http://github.com/vrm-c/UniVRM/releases/tag/v0.67.0) [milestone](https://github.com/vrm-c/UniVRM/milestone/27?closed=1) |                             | メンテナンスリリース                                                         |

[^springcollider]: スプリングボーンのコライダーの座標変換バグ。 [\#576](https://github.com/vrm-c/UniVRM/issues/576)
[^jpg]: エクスポートダイアログのスクリーンショットボタンの jpg バグ。[\#639](https://github.com/vrm-c/UniVRM/issues/639)
[^keywordmap]: シリアライザのバグ。エクスポートしたファイルの互換性。 [\#654](https://github.com/vrm-c/UniVRM/issues/654)
[^upm]: MeshUtility フォルダの移動と参照の問題。
[^asmdef]: 他のパッケージと併用するときに install で問題が出る？ [\#687](https://github.com/vrm-c/UniVRM/pull/687)
[^build]: build すると Exception( `#if UNITY_EDITOR` )。 [\#701](https://github.com/vrm-c/UniVRM/issues/701)
[^firstperson_import]: VRMFirstPerson のエディターインポートのバグ [/#515](https://github.com/vrm-c/UniVRM/issues/515)

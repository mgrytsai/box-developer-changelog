---
applied_at: '2022-02-16'
applies_to:
  - sdks
  - python
is_impactful: false
is_new_feature: true
release_source_url: 'https://github.com/box/box-python-sdk/releases/tag/v3.1.0'
collapse: true
is_index: false
category_id: changelog
subcategory_id: ''
id: 2022-02-16-box-python-sdk-v310-released
rank: null
total_steps: null
type: changelog
sibling_id: ''
parent_id: changelog
next_page_id: 2022-02-16-client-credentials-support-in-the-sdks
previous_page_id: 2022-02-14-new-box-shield-event-field
source_url: >-
  https://github.com/box/box-developer-changelog/blob/main/content/2022/02-16-box-python-sdk-v310-released.md
published_at: '2022-02-16'
fullyTranslated: true
---
# Box Python SDK `v3.1.0`のリリース

### 新機能と機能強化

* Python 3.10のサポートを追加 ([#692][1]) ([`d4aed82`][2])
* Python 3.8、Python 3.9、`pypy-3.7`、および`pypy-3.8`のサポートを追加 ([#689][3]) ([`0aa94cc`][4])
* ファイル/フォルダの`MDQ`にある`use_index`パラメータを廃止 ([#666][5]) ([`2595720`][6])
* 外部パッケージの`mock`をPython標準ライブラリの`unittest.mock`に置き換え ([#697][7]) ([`6fd6366`][8])
* 暗号化技術ライブラリを最新バージョンにアップグレード ([#668][9]) ([`9c94d08`][10])、[#667][11]をクローズ

### バグ修正

* 再試行の上限に達したときに`UploadSession.commit`によって`None`が返される ([#696][12]) ([`9456fe0`][13])
* `create_upload_session`に欠落している`api_call`デコレータを追加 ([#686][14]) ([`3510d3a`][15])
* 分割アップロードを修正 ([#673][16]) ([`2605fd7`][17])、[#671][18]をクローズ

[1]: https://github.com/box/box-python-sdk/issues/692

[2]: https://github.com/box/box-python-sdk/commit/d4aed82831af97305bace9a4588d27b23856c306

[3]: https://github.com/box/box-python-sdk/issues/689

[4]: https://github.com/box/box-python-sdk/commit/0aa94cc8a5c4db0fc204b27a60690b73c98a89cb

[5]: https://github.com/box/box-python-sdk/issues/666

[6]: https://github.com/box/box-python-sdk/commit/25957204b82c878e15dc3d118505a741171e9772

[7]: https://github.com/box/box-python-sdk/issues/697

[8]: https://github.com/box/box-python-sdk/commit/6fd63667aa7da4c794b4fb880d5c2949efe0073f

[9]: https://github.com/box/box-python-sdk/issues/668

[10]: https://github.com/box/box-python-sdk/commit/9c94d0878515dc75c1f267e2fb1f189a852772b6

[11]: https://github.com/box/box-python-sdk/issues/667

[12]: https://github.com/box/box-python-sdk/issues/696

[13]: https://github.com/box/box-python-sdk/commit/9456fe0124f4ac4e9c8a7bcc49039f07f310c477

[14]: https://github.com/box/box-python-sdk/issues/686

[15]: https://github.com/box/box-python-sdk/commit/3510d3ac085767205854014ecef80fd078d71773

[16]: https://github.com/box/box-python-sdk/issues/673

[17]: https://github.com/box/box-python-sdk/commit/2605fd782396ad6e42bd11c10f846e771634b7a0

[18]: https://github.com/box/box-python-sdk/issues/671
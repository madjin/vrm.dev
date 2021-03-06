---
title: "UniVRMサンプルをインストールする"
date: 2020-09-02T12:29:28+09:00
weight: 4
tags: ["api"]
---

このセクションでは、[UniVRMパッケージをインストール]({{< relref "univrm_install.md" >}})したことを想定しています。

## UniVRMサンプルのパッケージ

https://github.com/vrm-c/UniVRM/releases

`UniVRM-samples-0.XX.X_XXXX.unitypackage`

です。

## インポート

メニューから `Assets -> Import Package -> Custom Package` で `UniVRM-samples-0.XX.X_XXXX.unitypackage` を選択します。

以下の画像ようにインポートウィンドウを見たら、`Import`ボタンをクリックしてください：

{{< img src="images/vrm/sample_package_import.jpg" width="300" height="300" alt="sample_package_import" >}}

## UniVRMサンプルのシーンを実行する

`VRM.Samples`フォルダは`Assets`にあります。プロジェクトウィンドウに`SampleViewer`を選択します：

{{< img src="images/vrm/sample_scene.jpg" width="300" height="300" alt="sample_scene" >}}

`Game`タブをクリックして、`SampleViewer`のインタフェースを表示させます：

{{< img src="images/vrm/sample_viewer.jpg" width="500" alt="sample_viewer" >}}

`Play`ボタンをクリックして`SampleViewer`を有効になります。実行時に`Open`ボタンをクリックしてVRMモデルをシーンにインポートします：

{{< img src="images/vrm/play_mode.jpg" width="150" alt="play_mode" >}}
<br>
<br>
{{< img src="images/vrm/sample_viewer_activate.jpg" width="600" alt="sample_viewer_activate" >}}

`VRM.Samples`に[ランタイムVRMエクスポート](https://github.com/vrm-c/UniVRM/blob/master/Assets/VRM.Samples/Scripts/VRMRuntimeExporter.cs)と[一人称レンダリング](https://github.com/vrm-c/UniVRM/blob/master/Assets/VRM.Samples/Scripts/VRMRuntimeLoader.cs)のサンプルがあります。

Aliciaモデルは[こちら](https://github.com/vrm-c/UniVRM/blob/master/Tests/Models/Alicia_vrm-0.51/AliciaSolid_vrm-0.51.vrm)。

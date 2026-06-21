# 小班ジャンプ　小班JUMP Shohan-JUMP

This is a QGIS plugin to search and display the "Shohan" (small forest compartments) of Japan's National Forests.

日本の国有林で使用されている GIS データについて、特定の小班を検索して表示するための QGIS プラグインです。

## Overview / 概要

The plugin selects a specific Shohan based on its attribute values (forest compartment main number, sub-compartment name, and sub-compartment branch number) and centers it on the map canvas.

属性テーブルの情報（林班主番・小班名・小班枝番）に基づき、特定の小班を選択状態にしてマップキャンバスの中央に表示します。

## Usage / 使い方

1. Open the plugin from the toolbar / menu. / ツールバーまたはメニューからプラグインを起動します。
2. Choose the target layer of National Forest GIS data. / 対象となる国有林 GIS データのレイヤを選択します。
3. Enter the values to search: forest compartment main number (林班主番), sub-compartment name (小班名), and sub-compartment branch number (小班枝番). / 検索する林班主番・小班名・小班枝番を入力します。
4. Run the search. The matching Shohan is selected and centered on the map canvas. / 検索を実行すると、該当する小班が選択され、マップキャンバス中央に表示されます。

## License

GNU General Public License v3.0. See [LICENSE](LICENSE).

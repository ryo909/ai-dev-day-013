# Day013 Story — Meal Prep Slotter

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day013専用にテーマをseed固定して再生成時の見た目を安定化
- health用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: meal_batching
- Mechanic: process_ordering
- Input/Output: ingredient_list -> prep_timeline
- Audience Promise: lower_daily_friction
- Publish Hook: 平日の料理負担を先に潰す
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Add 2 safe enhancement components from selected_components while keeping the app single-page and stable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day013｜Meal Prep Slotter
平日の食事準備を短時間で回すための作り置き計画ツール。（話題:HN Frontpage）

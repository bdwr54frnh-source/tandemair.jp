# Cloudflare Pages 移行メモ（ロリポップ並行）

**記録:** 2026-08-08  
**依頼:** 社長  

## やること / やらないこと

### 今やる
- リニューアル版を Cloudflare Pages（無料）へ公開
- GitHub 連携で Push → 自動公開

### 今やらない
- 現行ホームページ（ロリポップ）の内容変更
- 独自ドメインの切替
- メール設定の変更
- 有料プランの契約
- ロリポップ解約（移行完了後に案内）

## 公開用ソース

ローカル: `AirQuick_Final_3/airface-homepage-pages/`  
GitHub: 既存 Private **`AirQuick_Final_3`**（新規リポジトリは作らない）  
Pages Root directory: `airface-homepage-pages`  
（現行ロリポップ用の作業フォルダ `waseda-inspection/` とは分離。現行公開は変更しない）

## ロリポップ解約（後で）

新HP・メール移行完了・動作確認後:
1. 独自ドメインの DNS を Cloudflare 側へ切替済みであること
2. メール移行完了・受信確認
3. ロリポップの自動更新停止
4. 解約手続き（管理画面の案内に従う）

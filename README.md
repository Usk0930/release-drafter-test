# release-drafter-test
Release Drafterの動作確認用のリポジトリ

# logs

## 1
- owned-ec-frontendと同等の設定を追加

## 2
- 差分の参照先をPR作成時点のheadコミットとなるよう修正

## 3
- 複数のPRによる差分が正しく反映されるか確認

## 4
### owned-ec-frontend反映前の確認
- featureタグが反映されること
- fixタグが反映されること
- dependenciesタグが反映されること
- タグなしがOthersに反映されること

## 5
- develop以外のブランチからmainへのPR作成時に差分が正しく反映されるか確認

## 6
### owned-ec-frontend反映前の確認#2
- featureタグが反映されること
- fixタグが反映されること

## 7
### owned-ec-frontend反映前の確認#3
- developブランチからmainへのPR作成時に差分が正しく反映されるか確認
- featureタグが反映されること

## 8
- developブランチからmainへのPR作成時に差分が正しく反映されるか確認

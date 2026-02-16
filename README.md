# Vending App

## Purpose
ユーザーが自販機の写真と位置情報を投稿し、
共有できるプラットフォームを構築する

## Environment
Flutter 3.x
Android API 34

## MVP
ユーザーがGoogleログインし、自販機の写真を撮影し、位置情報と登録日とともにクラウド保存し、一覧で閲覧できるアプリ

### 含まれるもの
Googleログイン
写真撮影または選択
位置情報取得（緯度・経度）
Firebase Storageに画像保存
Firestoreにメタデータ保存
一覧表示
詳細表示

### 含まれないもの（今はやらない）
地図表示
商品情報の構造化
OCR
編集／削除
コメント
いいね
検索
UI装飾

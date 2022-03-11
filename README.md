# VFX-Template

## Hou to use

1. Git HubからCloneする（個人アカウントのため github.com.**private**）
2. download後、フォルダ名を任意にリネーム
3. Git GUIで新しいリポジトリとして登録（VFX-Templateリポジトリを上書きしないように）

## **VFX-Template**

**・全てのHDRPサンプルシーン素材の削除**

**・Edit＞ProjectSetting＞HDRPDefaultSetting＞**

```
Default Volume Profile Asset
	すべての項目を削除
DefaultLookDevProfile
	すべてのチェックを外す
	※項目の削除ができなかったため

```

**・Edit＞ProjectSetting＞Editor**

```
Version Control＞Mode
	Meta Filesに変更
Asset Serialization＞Mode
	Force Textに変更（Binary形式でなく、Text化）

```

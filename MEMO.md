# terraformコマンドのメモ書き
### 設定ファイルの初期化
```sh
$ terraform init
```
![terraform init](./images/terraform_init.png)
### コードの整形
```sh
$ terraform fmt
```
### 構文のチェック
```sh
$ terraform validate
```
問題がない場合  
![terraform validate success](./images/terraform_validate_success.png)
### ドライラン
```sh
$ terraform plan
```
### 実効
```sh
$ terraform apply
```
### リソースの削除
```sh
$ terraform destroy
```

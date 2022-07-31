## config

- 一覧
    - ```sh
      gcloud config configurations list
      ```
- 切り替え
    - ```sh
      gcloud config configurations activate default
      ```


## sql

- sqlへログイン
    - gcloudのconfig指定済みの環境へ
    - ```sh
      gcloud sql connect main --user=origin_dev --quiet
      ```

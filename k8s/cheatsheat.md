## k8sのセットアップ

```sh
brew install kubctl
```

krewをinstall
https://krew.sigs.k8s.io/docs/user-guide/setup/install/

projectを切り替えるためctxをいnstall
```
kubectl krew install ctx ns
```


## ctxを使った環境切り替え

```sh
kubectl ctx
```


## Pod操作

- pod一覧
    - ```sh
      kubectl get pod
      ```
- pod詳細確認
    - ```
      kubectl describe pod [pod-name]
      ```
- podへログイン
    - ```markdown
      kubectl exec --stdin --tty [pod-name] -- /bin/bash
      ```

# GitHub Actions を用いた CI/CD
GitHub Actions を用いた Ci/CD の練習用コード。<br>
GitHub Actions を用いて、`git push` をトリガーに、以下の CI/CD 処理を自動的に行う

- ローカル環境での CI/CD : <br>
	[![build and deploy api on local env](https://github.com/Yagami360/github-actions_exercises/workflows/build%20and%20deploy%20api%20on%20local%20env/badge.svg)](https://github.com/Yagami360/github-actions_exercises/actions?query=workflow%3A%22build+and+deploy+api+on+local+env%22)<br>

	```sh
	$ sh run_ci_cd_local.sh
	```
	1. `git push` をトリガーに、API コードの docker image を作成
	1. リクエスト処理を実行し、正しいレスポンスが返ってくるか確認

<!--
- GKE 環境での CI/CD<br>
	```sh
	$ sh run_ci_cd_gke.sh
	```
	1. `git push` をトリガーに、Google Container Registry に API コードの docker image をアップロード
	1. GKE クラスタ作成
	1. 
-->

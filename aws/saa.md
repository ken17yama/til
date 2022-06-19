# SAAの勉強メモ
間違ったり、理解が足りてないところを中心にメモする。

- S3
	- Intelligent-Tiering
		- オーバーヘッドなしでオブジェクトの可用性、パフォーーマンスまたは耐久性に影響を与えることなく、ストレージコストを自動的に最適化するのに役立つ。
			- オーバーヘッド：付加的な処理や設定
			- 可用性：利用可能な状態を維持する能力
		- 取り出し料金はかからない
- NATゲートウェイ
	- **プライベートサブネット内のインスタンスにインターネットへのアクセスを提供**する。
	- NATゲートウェイ自体は**パプリックサブネットに配置**する必要がある。
- Transit Gateway
	- VPCとオンプレミスを中央ハブで接続する。  ![image](https://user-images.githubusercontent.com/53633841/174489500-4a767f50-4b6c-4afb-9092-df857f7f8fc5.png)
		- 参考：https://aws.amazon.com/jp/transit-gateway/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc
- Aurora
	- **MySQLおよびPostgreSQL**との完全な互換性を持つ。
		- 参考：https://aws.amazon.com/jp/rds/aurora/
		- 

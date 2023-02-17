# hugging facewを使って wavlmを学習するためのスクリプトです。

## reazon upload method

```bash
tar cf - reazon | gzip --best | aws s3 cp - <バケットURL> --endpoint-url=<wasabi URL>
```

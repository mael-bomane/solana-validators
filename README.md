# Solana Validators

```bash
curl -H "Accept: application/json" -H "Authorization: Bearer $API_KEY" https://api.solanabeach.io/v2/validator-list | jq . > validator-list.json && 'ssh -i ~/.ssh/id_ed25519' git add . && git commit -m "Last Update : $(date +"%Y-%m-%d %H:%M:%S")" && git push
```

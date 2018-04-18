# go_for_bloke
blockchain thinking

## BPM example from:

https://medium.com/@mycoralhealth/code-your-own-blockchain-in-less-than-200-lines-of-go-e296282bcffc

## running script

requires go (`brew install go`)

requires local host setting of environment through creating a .env file in root directory containing:

```ADDR=8080```

Executing script

```go run main.go```

## cURL post 

Demo push a new entry to the ledger. Variable is 'BPM'. 

curl  -H "Content-Type: application/json" -d "{\"BPM\": 57}" http://localhost:8080

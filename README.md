# commonmanagement

Serverless mail and ops files (mail with rewards, maintenance, force update) for B-SGL games. Each game file is signed (RSA-2048, PKCS#1 v1.5, SHA-256); games verify the signature before using it.

- `games/<game>/ops.json` + `ops.json.sig` - published files (written only by the operator console)
- `spec/OPS_SPEC.md` - format and what a game app must do (Korean)

The operator console and the private keys live only on the operator's PC; they are never stored here.

# commonmanagement

Serverless ops files (notices, maintenance, force update, mail) for B-SGL games. Each game file is signed (RSA-2048, PKCS#1 v1.5, SHA-256); games verify the signature before using it.

- `spec/OPS_SPEC.md` - format (Korean)
- `console/ops_console.html` - operator console (open locally in Chrome/Edge)
- `games/<game>/ops.json` + `ops.json.sig` - published files

Private keys are never stored here.

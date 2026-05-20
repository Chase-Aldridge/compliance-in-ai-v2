# Compliance in AI V2

Rebuilt edition of the "Compliance in AI" talk for AI Pioneers Club Denver, in the design language of [impeccable.style](https://impeccable.style/). Single-file Reveal.js 5.1.0 deck. Eighteen slides on personal vs enterprise AI governance, framed as classical mechanics versus quantum mechanics.

V1 lives at [compliance-in-ai](https://github.com/Chase-Aldridge/compliance-in-ai) and serves at `compliance.chasealdridge.com`. V2 serves at `compliance-v2.chasealdridge.com`.

## Local preview

```
python3 -m http.server 8765
```

Open `http://localhost:8765`. Press `S` for presenter view with speaker notes.

## Deploy (Coolify)

```
curl -X POST -A "Mozilla/5.0" \
  -H "Authorization: Bearer $(jq -r .cloud.token ~/.config/coolify/config.json)" \
  "https://coolify.tenanttalk.info/api/v1/deploy?uuid=$COOLIFY_APP_UUID&force=true"
```

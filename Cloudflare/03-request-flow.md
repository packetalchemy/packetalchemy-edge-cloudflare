# Request Flow in Cloudflare

## 🌍 Flow

```
Client → DNS → Cloudflare Edge → WAF → Worker → Origin Server
```

---

## ⚠️ Key Points

- DNS decides routing
- WAF filters traffic
- Worker modifies request
- Origin serves content

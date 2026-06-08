# Cloudflare Edge Computing – Introduction

## 🧠 What is Edge Computing?

Edge computing means processing requests closer to the user instead of central servers.

---

## ☁️ Cloudflare Role

Cloudflare acts as:
- Reverse proxy
- Security layer (WAF)
- DNS resolver
- Edge compute platform (Workers)

---

## 🌍 Request Flow

```
User → Cloudflare Edge → Origin Server
```

---

## 🔥 Telecom Analogy

| Cloudflare | Telecom Equivalent |
|------------|------------------|
| Edge node | SGW / UPF decision point |
| DNS routing | PGW selection logic |
| WAF | Firewall / DPI |

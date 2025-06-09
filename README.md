# 🧩 Nginx Production Configs

Reusable, secure, and modular Nginx configuration templates for deploying React, Flask, static websites, or APIs.

## Structure

```
nginx-configs/
├── README.md
├── nginx.conf
├── snippets/
│   └── security-headers.conf
├── sites-available/
│   └── site.template
```

## Instructions

1. Copy `nginx.conf` to `/etc/nginx/nginx.conf`
2. Use `sites-available/site.template` as your domain config template
3. Optional: include `snippets/security-headers.conf` in your server blocks
4. Reload Nginx after changes: `sudo nginx -t && sudo systemctl reload nginx`

🚀 Built by Qani, the stone-cold DevOps warrior.

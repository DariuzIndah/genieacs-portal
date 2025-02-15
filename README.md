# GenieACS Portal

Portal manajemen perangkat untuk GenieACS.

## Fitur

- Login dengan tag perangkat
- Dashboard client
- Manajemen WiFi (SSID & Password)
- Dashboard admin
- Manajemen tag perangkat
- WhatsApp Bot integration

## Instalasi

1. Clone repository
2. Install dependencies:
```bash
npm install
```

3. Copy .env.example ke .env dan sesuaikan:
```bash
cp .env.example .env
```

4. Jalankan aplikasi:
```bash
node app.js
```

## Konfigurasi

Edit file .env dengan konfigurasi yang sesuai:

- GENIEACS_URL=http://your-genieacs-server:7557
- GENIEACS_USERNAME=admin
- GENIEACS_PASSWORD=admin
- PORT=3001

## Teknologi

- Node.js
- Express
- EJS
- GenieACS API
- WhatsApp Bot

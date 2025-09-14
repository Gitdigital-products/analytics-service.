# analytics-service.
analytics-service.# Analytics Service  Tracks events and usage metrics across the **Gitdigital Products** ecosystem.  ## 🚀 Features - `POST /track` → Track an event (login, purchase, search, etc.) - `GET /metrics` → Retrieve basic counts by event type - Uses in-memory event store for now - Includes timestamps + metadata for richer analytics  
# Analytics Service

Tracks events and usage metrics across the **Gitdigital Products** ecosystem.

## 🚀 Features
- `POST /track` → Track an event (login, purchase, search, etc.)
- `GET /metrics` → Retrieve basic counts by event type
- Uses in-memory event store for now
- Includes timestamps + metadata for richer analytics

## 🛠️ Setup
```bash
cargo run

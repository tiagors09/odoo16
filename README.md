# Course Odoo (`odoo`)

Base project structure for running Odoo 16 via Docker Compose and developing custom addons with JSON-RPC API endpoints.

## Technologies and Versions

- Odoo 16.0, defined by the `odoo:16.0` image in `compose.yaml`.
- PostgreSQL 15.
- pgAdmin via the `dpage/pgadmin4:latest` image.
- Python `>=3.12` managed locally via `uv` (the Odoo server runs inside the Docker container).

## Project Structure

```text
.
├── compose.yaml
├── config/
│   └── odoo.conf
├── addons/          <-- Place your custom modules here
└── .env.example
```

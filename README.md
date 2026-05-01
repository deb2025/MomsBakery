# MomsBakery Online Cake Ordering Platform

Monorepo scaffold implementing an end-to-end microservices architecture for online cake ordering.

## Services
- api-gateway (Spring Cloud Gateway)
- auth-user-service
- catalog-inventory-service
- order-cart-service
- payment-service
- tracking-notification-service (WebSocket + tracking events)
- frontend (React customer app)
- admin-dashboard (React admin panel)
- delivery-pwa (React PWA)

## Run
```bash
docker compose up --build
```

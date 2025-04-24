# Logistics Webhook Simulator

Simulate webhook responses for logistics platforms to test integrations and event handling.

```bash
curl -X POST https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/ \
  -H "Content-Type: application/json" \
  -d '{"shipment_id":"SHIP123456","event":"shipment_delivered","timestamp":"2025-04-24T14:01:21Z"}'

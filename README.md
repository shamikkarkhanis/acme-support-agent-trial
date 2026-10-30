# Acme Shop Support API

A small customer-support agent exposed as an HTTP API, used as a red-teaming test target.

- `POST /v1/chat` sends a customer message to an LLM support assistant.
- `GET /v1/help/search` searches help-center articles.
- `GET /v1/orders/{order_id}` returns one of the caller's orders.

All data is fake. Run with `uvicorn app:app` and `LC_GATEWAY_KEY` set.

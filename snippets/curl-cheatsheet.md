# curl cheatsheet

- GET
  curl -i https://example.com

- JSON POST
  curl -X POST https://example.com/api \
    -H "Content-Type: application/json" \
    -d '{"ping":"pong"}'

# HTTP Analysis Notes

## Scope
- Client-server request flow
- Request methods (GET, POST, PUT, DELETE)
- Status code interpretation
- Request and response header review
- CORS-related response header observations
- Network timeline behavior in Chrome DevTools

## Highlights
- Successful requests were mostly observed with 200 OK and 204 No Content.
- Error scenarios were observed with 400 Bad Request during invalid/failed form submission flows.
- Redirect behavior was observed with 301 Moved Permanently in account-route access.
- Gateway endpoints under apigw.trendyol.com exposed service-level API interactions behind UI actions.

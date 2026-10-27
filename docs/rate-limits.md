# Rate limits

The API accepts up to 100 requests per minute per token.
Requests over the limit get a 429 response with a Retry-After header.

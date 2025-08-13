# OEH Web Components

## Test and run it
Simply run:

```bash
docker compose up
```
Then, open http://localhost:8001 in your browser to see the sample usage page.

## Modifying
When you want to modify the index.html, make sure to call
```bash
docker compose build
```
## Using OEH web components
Check that your webserver either proxies the XHR requests to edu-sharing (see nginx.conf), or, ask our team to allow access from your domain.

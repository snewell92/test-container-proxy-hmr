# Test HMR Nginx Reverse Proxy

This is a test docker compose setup to isolate and test
how to get websockets upgraded through containers.

You should `cd` into `/app` and run `npm ci` or `npm install`
first, then run `docker-compose up -d` in this folder.

You can make changes to the `nginx/nginx.conf` file and do
`docker-compose restart proxy` to see the changes live.

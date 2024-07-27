# Startup bundle with docker compose

1. install a local setup with docker compose

```
git clone https://github.com/malach-it/opencred.git
cd opencred/docker-compose
docker compose up
```

Be patient, the install of the npm packages takes a while.

2. Navigate to the openid server to trigger an opencred login

http://localhost:4000/oauth/authorize?client_id=00000000-0000-0000-0000-000000000001&redirect_uri=http://redirect.uri.boruta&response_type=code&scope=openid

Note: You can access the openid provider on http://localhost:4001 with the credentials admin@test.test / imaynotknowthat

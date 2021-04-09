## About

Laravel Docker container based on https://github.com/laravel/octane and Roadrunner meant for CI / production.

## Run and build

```
docker build -t octane .
docker run -e APP_KEY=your_app_key_here -p 8080:8080 -d octane
```

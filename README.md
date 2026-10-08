# Docker HTML Static Web - Session 09

## Build Image

```bash
docker build -t my-html-app:v1 .
```

## Run Container

```bash
docker run -d -p 8081:80 --name html-app my-html-app:v1
```

## Test

```bash
curl http://localhost:8081
```

## Expected Result

```text
<h1>Hello Docker Session 09!</h1>
```

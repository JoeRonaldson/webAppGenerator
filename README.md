### Building and run without Docker

```bash
nvm use
npm install
npm run start
```

### Building and running with Docker

```bash
npm run docker
```

This script is a shortcut executing the following commands:

```bash
docker build -t template-node-express .
docker run -it -p 7860:7860 template-node-express
```

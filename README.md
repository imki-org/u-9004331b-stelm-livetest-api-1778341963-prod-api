# api



## Getting Started

This is a Node.js Express backend service bootstrapped for the Stelm MVP platform.

### Development

```bash
npm install
npm run dev
```

The server will run on [http://localhost:3000](http://localhost:3000).

### Production

```bash
npm install
npm start
```

### Docker

```bash
docker build -t imki-org/u-9004331b-stelm-livetest-api-1778341963-prod-api .
docker run -p 3000:3000 imki-org/u-9004331b-stelm-livetest-api-1778341963-prod-api
```

## API Endpoints

- `GET /health` - Health check endpoint
- `GET /api` - API information
- `GET /api/data` - Example data endpoint

## Project Structure

```
src/
  └── index.js        # Main application entry point
.env.example          # Environment variables template
Dockerfile            # Docker configuration
package.json          # Node.js dependencies
```

## Environment Variables

Copy `.env.example` to `.env` and configure:

```bash
cp .env.example .env
```

## Learn More

- [Express Documentation](https://expressjs.com/)
- [Node.js Documentation](https://nodejs.org/)

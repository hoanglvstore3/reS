<p align="left">
  <a href="http://var-meta.com/" target="blank"><img src="https://www.var-meta.com/images/logo_light.svg" width="200" alt="Var meta Logo" /></a>
</p>

# 🚀 Rabid Admin Backend

> A modern and powerful backend API service providing comprehensive management capabilities for the Rabid system with robust architecture and advanced features.

## 🛠️ Core Technologies

- **Backend**: NestJS + TypeScript + Express
- **Database**: PostgreSQL with TypeORM
- **Authentication**: JWT with Redis sessions
- **File Handling**: Multer with cloud storage
- **Queue Management**: BullMQ for background job processing

## 📦 Installation

### Prerequisites
- Node.js (v18+)
- PostgreSQL (v14+)
- Redis (v6+)
- pnpm package manager

### Setup

1. **Clone and install dependencies**
```bash
git clone <repository-url>
cd rabid/admin-be
pnpm install
```

2. **Environment configuration**
```bash
# Copy environment template
cp .env.example .env

# Configure your environment variables:
# - Database connection
# - Redis connection
# - JWT secrets
# - SendGrid API key
# - File storage settings
```

## 🚀 Running the Application

### Development Mode

```bash
# Development server (watch mode)
pnpm run dev

# Start development server
pnpm run start

# Type checking
pnpm run lint

# Database migrations
pnpm run migration:run
```

The API will start on [http://localhost:3000](http://localhost:3000).

### Production Mode

```bash
# Build the application
pnpm run build

# Start production server
pnpm run start:prod
```

## 🏁 Getting Started

1. Follow the [Installation](#-installation) steps
2. Configure your database and Redis connections in `.env`
3. Run database migrations if needed
4. Start the development server using commands in [Running the Application](#-running-the-application)
5. Access the API documentation at [http://localhost:3000/api](http://localhost:3000/api)

## 📚 Learn More

To learn more about NestJS, take a look at the following resources:

- [NestJS Documentation](https://docs.nestjs.com/) - learn about NestJS features and API.
- [TypeORM Documentation](https://typeorm.io/) - database ORM documentation.

You can check out [the NestJS GitHub repository](https://github.com/nestjs/nest) - your feedback and contributions are welcome!

## 🌐 Deployment

The application can be deployed using Docker:

```bash
# Build Docker image
docker build -t rabid-admin-backend .

# Run with Docker Compose
docker-compose up -d
```

Check out the deployment scripts in the `scripts/` directory for more deployment options.

## 📞 Stay in touch

- Powered by - [Var Meta](https://var-meta.com)
- Website - [https://var-meta.com](https://var-meta.com/)

## 📝 License

NestJS is [MIT licensed](LICENSE).

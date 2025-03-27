# Lotus Doors Customer Portal

A centralized web portal for Lotus Doors providing access to AI tools, resources, and education.

## Project Overview

The Lotus Doors Customer Portal is a web-based platform designed to provide Lotus Doors with access to various AI-powered tools, resources, and educational content. This portal serves as a central hub for interaction with Natural Velocity's AI solutions.

### Key Features

- **Blueprint Section**: Strategic roadmap and planning information
- **Education Section**: AI educational content featuring IBM Technology YouTube videos
- **Guidelines Section**: Usage instructions and best practices
- **Automations Section**: Access to automation tools
- **ChatBots Section**: Interfaces to AI-powered chatbots

## Technology Stack

- Containerized architecture using Docker and docker-compose
- Web-based interface with responsive design
- Secure authentication and access control
- Support for both cloud and hybrid deployments

## Installation

### Prerequisites

- Docker and docker-compose installed
- Git for repository cloning

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd lotus-doors-portal
   ```

3. Start the containers:
   ```bash
   docker-compose up -d
   ```

4. Access the portal at `http://localhost:<port>` (default port will be configured in docker-compose.yml)

## Development

The solution blueprint can be accessed using the environment variable:
```bash
# Set the environment variable for the blueprint location
export LOTUS_BLUEPRINT_PATH="path/to/blueprint"

# Access the blueprint using the environment variable
cd $LOTUS_BLUEPRINT_PATH
```

For Cursor development, you can reference this environment variable in your scripts or commands.

### Project Structure

```
.
├── docs/                    # Documentation
├── images/                  # Image assets
├── memory-bank/             # Project context and tracking
├── src/                     # Source code
│   ├── components/          # UI components
│   ├── sections/            # Portal sections
│   └── services/            # Backend services
└── docker-compose.yml       # Container configuration
```

## Deployment

The portal is designed for:
- Cloud deployment
- Hybrid environment deployment
- Local deployment using Docker

## Security

This project implements security best practices including:
- Secure authentication
- Controlled network access
- Data protection

## License

This project is proprietary and confidential to Natural Velocity and Lotus Doors.

## Contact

For more information, contact:
- Natural Velocity: [https://naturalvelocity.ai](https://naturalvelocity.ai)
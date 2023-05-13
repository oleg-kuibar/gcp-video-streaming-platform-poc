# Video Streaming Platform POC Project

This is a proof-of-concept project for a video streaming platform built using React, GraphQL/Apollo, and Google Cloud Platform (GCP) services. The platform allows users to upload, stream, and view high-quality videos with a responsive and user-friendly UI.

## Features

- Upload videos with support for popular formats such as MP4, AVI, and MOV
- Stream videos with high-quality playback and adaptive bitrate support
- User-friendly UI with responsive design and intuitive navigation
- Secure authentication and authorization using JSON Web Tokens (JWT) and Single Sign-On (SSO) with OAuth
- High-performance and high-availability with GCP services such as Compute Engine, Cloud Storage, Cloud CDN, and Load Balancer
- GraphQL and Apollo for efficient data fetching and optimized performance

## Technologies Used

- JavaScript
- TypeScript
- React
- GraphQL/Apollo
- Next.js
- Google Cloud Platform (GCP)
- Docker

## Getting Started

1. Clone the repository
2. Install dependencies with `pnpm install`
3. Start the development server with `pnpm run dev`

## Deployment

This project can be deployed to GCP using Docker containers. The following steps outline the deployment process:

1. Build Docker images for the front-end and back-end services
2. Push the images to Google Container Registry
3. Create a Kubernetes cluster in GCP
4. Create a Kubernetes deployment that specifies the Docker images to use
5. Create a Kubernetes service that exposes the deployment
6. Use a Load Balancer to route traffic to the Kubernetes service

## Testing

This project includes automated tests for both the front-end and back-end services. To run the tests, use the following command:

```npm run test```

## Security

This project adheres to best practices for security in web applications and protects against common vulnerabilities such as those listed in the OWASP Top 10.

## Contributing

This project is open for contributions. If you find a bug or want to suggest a new feature, please open an issue or submit a pull request.

## Links

[UI Kit](https://www.figma.com/community/file/1165192525323846383/Video-Conferencing-Kit-and-Live-Streaming-UI-Kit)

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

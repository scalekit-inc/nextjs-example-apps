<p align="center">
  <a href="https://scalekit.com" target="_blank" rel="noopener noreferrer">
    <picture>
      <img src="https://cdn.scalekit.cloud/v1/scalekit-logo-dark.svg" height="64">
    </picture>
  </a>
</p>

<h1 align="center">
  Scalekit Next.js Example Apps
</h1>

<p align="center">
  <strong>Auth stack for AI apps ⚡ Human auth capabilities</strong>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@scalekit-sdk/node"><img src="https://img.shields.io/npm/v/@scalekit-sdk/node.svg" alt="npm version"></a>
  <a href="https://github.com/scalekit-inc/nextjs-example-apps/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"></a>
  <a href="https://docs.scalekit.com"><img src="https://img.shields.io/badge/docs-scalekit.com-blue" alt="Documentation"></a>
</p>

<p align="center">
  Production-ready Next.js applications demonstrating enterprise authentication patterns with Scalekit
</p>

## 🚀 Available Examples

### 1. Webhook Events Handler
**Real-time event processing for enterprise workflows**

- **Secure Webhook Endpoints**: Signature validation and payload verification
- **Event Processing Pipeline**: Handle user lifecycle, organization, and connection events  
- **Next.js API Routes**: Serverless function patterns for webhook handling
- **Error Handling**: Comprehensive logging and retry mechanisms

### 2. Full Stack Authentication
**Complete enterprise authentication flow**

- **OAuth 2.0 Integration**: Authorization code flow with PKCE
- **Hosted Login Box**: Customizable authentication UI
- **Session Management**: Secure JWT handling with HTTP-only cookies
- **Route Protection**: Middleware-based authentication guards
- **User Context**: React hooks for authentication state

### 3. AWS Cognito SSO Integration
**Enterprise SSO bridging with AWS Cognito**

- **OIDC Protocol**: Seamless integration between Cognito and Scalekit
- **Enterprise Identity Providers**: SAML/OIDC federation support
- **Iron Session Security**: Encrypted session storage
- **Responsive Design**: Tailwind CSS with mobile-first approach
- **Protected Routes**: App Router compatible middleware

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- ScaleKit credentials (client ID and secret)
- .env file with required environment variables

### Installation

1. Clone this repository
2. Navigate to the desired example directory
3. Run `npm install` or `yarn` to install dependencies
4. Create a `.env` file with your ScaleKit credentials (see `.env.example` in each project)
5. Run `npm run dev` or `yarn dev` to start the development server

## Environment Variables

Each example requires specific environment variables. Check the `.env.example` file in each project directory for details.

## Support

For assistance, please contact ScaleKit support or open an issue in this repository.

## Key Features Across All Examples

- **Enterprise SSO**: SAML 2.0 and OIDC protocol support
- **User Management**: Organization user lifecycle management
- **Directory Sync**: SCIM 2.0 automated user provisioning  
- **Admin Portal**: Embeddable interface for IT administrators
- **Webhook Events**: Real-time notifications for user and organization changes
- **Security**: JWT tokens, CSRF protection, and secure session management

## Additional Resources

- 📚 [Scalekit Documentation](https://docs.scalekit.com)
- 🔧 [API Reference](https://docs.scalekit.com/apis/)
- 🚀 [Full Stack Auth Quickstart](https://docs.scalekit.com/fsa/quickstart/)
- 🔗 [SSO Integration Guide](https://docs.scalekit.com/sso/quickstart/)
- 💬 [Community Examples](https://github.com/orgs/scalekit-developers/repositories)
- ⚡ [Next.js Example](https://github.com/scalekit-developers/scalekit-nextjs-demo)

## Contributing

We welcome contributions! Please feel free to submit a pull request with any improvements or additional examples.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

<p align="center">
  Made with ❤️ by <a href="https://scalekit.com">Scalekit</a>
</p>

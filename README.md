# Email Sender Application

A powerful desktop application for managing email campaigns with advanced features for template management, SMTP configuration, and email sending.

## Features

- **Template Management**: Create, edit, and manage HTML email templates with support for:
  - Variable substitution for personalized emails
  - Inline image embedding (base64/content ID)
  - Clickable image links
  - Encoded URLs for privacy and tracking
  - Template rotation

- **SMTP Configuration**:
  - Multiple SMTP server management
  - Configurable SMTP rotation with batch settings
  - Automatic failover on SMTP errors
  - Connection testing

- **Email Sending**:
  - Bulk email sending with customizable speed
  - CSV import for recipient lists
  - Email validation and cleaning
  - Detailed sending logs
  - Progress tracking

- **URL Encoding**:
  - Convert URLs to HTML entities format
  - Preserve encoded format in sent emails

## Technology Stack

- Electron.js for cross-platform desktop application
- React.js for the user interface
- Node.js for backend functionality
- SQLite for local data storage

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/email-sender.git
   cd email-sender
   ```

2. Install dependencies:
   ```
   npm install
   ```
   or
   ```
   yarn install
   ```

3. Start the development server:
   ```
   npm run dev
   ```
   or
   ```
   yarn dev
   ```

### Building for Production

```
npm run build
```
or
```
yarn build
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

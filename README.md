# Appghlam

Appghlam is a customized version of [Appsmith](https://appsmith.org), an open-source platform for building internal tools. This project was forked from the Appsmith GitHub repository and tailored to meet specific requirements.

## Features
- Rapid development of internal applications.
- Fully customizable UI components.
- Integration with various data sources and APIs.
- Advanced user role and permission management.
- Localization and support for RTL (Right-to-Left) layouts.

## Installation

Follow these steps to install and run Appghlam locally:

### Prerequisites
- Node.js (v16 or later)
- Docker and Docker Compose
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Namatek/appghlam.git
   cd appghlam
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the application using Docker Compose:
   ```bash
   docker-compose up
   ```

4. Access the application in your browser:
   ```
   http://localhost:8080
   ```

## Configuration

Modify the `.env` file to set up environment-specific configurations. For example:
```env
APPSMITH_HOST=localhost
APPSMITH_PORT=8080
APPSMITH_ENCRYPTION_KEY=<your-secret-key>
```

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature/my-new-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add my new feature"
   ```
4. Push your branch and create a pull request:
   ```bash
   git push origin feature/my-new-feature
   ```

## License

Appghlam is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

## Acknowledgments

Special thanks to the team at [Appsmith](https://appsmith.org) for their incredible work on the base platform. This project builds upon their efforts to provide a more tailored solution for our needs.

---
For more details, visit the original [Appsmith GitHub repository](https://github.com/appsmithorg/appsmith).

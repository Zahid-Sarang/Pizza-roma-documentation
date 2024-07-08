# Pizza-Roma

Pizza-Roma is a MERN stack-based micro-service application designed to streamline the operations of a chain restaurant. The project features two primary interfaces: an admin dashboard and a client-side application. The admin dashboard facilitates restaurant management, while the client-side application provides a seamless ordering experience for customers.

## Technologies Used

### Frontend
- **Next.js**
- **React**
- **TypeScript**

### Backend
- **Node.js**
- **Express.js**
- **TypeScript**

### Databases
- **MongoDB**
- **PostgreSQL**

### Authentication
- **JWT (JSON Web Token)**

### Deployment
- **Docker**
- **ArgoCD**
- **GitHub Actions**
- **AWS**
- **Kubernetes**

## Overview

Pizza-Roma is designed to provide an efficient and user-friendly experience for both restaurant managers and customers. The application is divided into two main parts:

1. **Admin Dashboard**: Provides comprehensive tools for restaurant managers to manage orders, inventory, staff, and customer feedback.
2. **Client Application**: Offers customers an intuitive and responsive interface for browsing the menu, placing orders, and tracking their delivery status.

## Objectives

### Admin Dashboard
- Manage orders efficiently.
- Track and control inventory.
- Handle staff management.
- Collect and review customer feedback.

### Client Application
- Browse the menu easily.
- Place orders seamlessly.
- Track delivery status in real-time.

## Getting Started

### Prerequisites
- Node.js
- Docker
- AWS Account
- Kubernetes Cluster

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/pizza-roma.git
    cd pizza-roma
    ```

2. **Install dependencies:**
    ```sh
    npm install
    ```

3. **Set up environment variables:**
    Create a `.env` file in the root directory and add the necessary environment variables.

4. **Run the application:**
    ```sh
    npm run dev
    ```

## Deployment

### Docker
- Ensure Docker is installed and running on your system.
- Build the Docker image:
    ```sh
    docker build -t pizza-roma .
    ```
- Run the Docker container:
    ```sh
    docker run -p 3000:3000 pizza-roma
    ```

### Kubernetes
- Ensure you have a Kubernetes cluster running.
- Apply Kubernetes configurations:
    ```sh
    kubectl apply -f k8s
    ```

### CI/CD
- The project uses GitHub Actions for continuous integration and deployment.
- The deployment pipeline is configured to use ArgoCD for continuous delivery to AWS.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

## Contact

For more information, please contact [your email address].

---

**Note:** This README file is a template and should be customized with your specific project details and configurations.
# Pizza-roma-documentation

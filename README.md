# Book Store MERN Stack Project

## Lessons

- [x] Lesson 01: Create Node.js project from scratch
- [x] Lesson 02: Create our first HTTP Route
- [x] Lesson 03: Add MongoDB and Mongoose to Node.js
- [x] Lesson 04: Create Book model with Mongoose
- [x] Lesson 05: Save a new Book with Mongoose
- [x] Lesson 06: Get All Books with Mongoose
- [x] Lesson 07: Get One Book by ID with Mongoose
- [x] Lesson 08: Update a Book with Mongoose
- [x] Lesson 09: Delete a Book with Mongoose
- [x] Lesson 10: Refactor Node.js with Express Router
- [x] Lesson 11: CORS Policy in Node.js and Express.js
- [x] Lesson 12: Create React Project, Vite, Tailwind CSS
- [x] Lesson 13: SPA and Add React Router DOM
- [x] Lesson 14: Show Books List in React
- [x] Lesson 15: Show Book Details in React
- [x] Lesson 16: Create Book in React
- [x] Lesson 17: Edit Book in React
- [x] Lesson 18: Delete Book in React
- [x] Lesson 19: Show Books List as Card
- [x] Lesson 20: Make Book Card a Single Component
- [x] Lesson 21: Add Book Modal
- [x] Lesson 22: Improve User Experience (UX) with Beautiful Alert

## Recent Updates

### Kubernetes Deployment

![mern](https://github.com/Saurabhkr952/Book-Store-MERN-Stack/assets/32189783/587b967d-4243-449f-b575-22e0fc4cd694)


In a recent update, I've extended the capabilities of this project by configuring it for Kubernetes (K8s) deployment. These changes include:

- **MongoDB Configuration**: I've made adjustments to the `backend/config.js` file to configure the MongoDB URL. This modification allows our backend to seamlessly interact with a MongoDB database deployed within our Kubernetes cluster.

- **Docker Image Optimization**: To ensure efficient image management, I've created Dockerfiles for both the backend and frontend components. These Dockerfiles are designed to use minimal base images, reducing image size and enhancing performance.

- **Development Environment Simplification**: A `docker-compose.yaml` file has been introduced to simplify the setup of the development environment. This Docker Compose file orchestrates the deployment of the application's components, streamlining development.

- **Kubernetes Manifests**: To further enhance the scalability and manageability of the project, I've added a series of Kubernetes manifests:

  - `frontend.yaml`: This file contains definitions for the frontend service and deployment.
  - `backend.yaml`: It includes configurations for the backend service and deployment.
  - `database.yaml`: This manifest defines the MongoDB deployment and service.
  - `database-secrets.yaml`: For enhanced security, MongoDB username and password are stored as secrets.
  - `mongo-express.yaml`: This file contains deployment and service definitions for the Mongo Express admin interface.
  - `mongo-express-secrets.yaml`: Safely stores MongoDB credentials and URL.
  - `ingress.yaml`: By configuring this file, we enable access to our application via the domain book-store.com.

These updates are strategically aimed at improving the project's scalability and making it easier to deploy and manage within a Kubernetes environment.

## Future Improvements

Our project is an ongoing work in progress, with plans for further enhancements in the pipeline. Stay tuned for more updates and new features!

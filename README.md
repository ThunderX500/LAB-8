# SEG3502 — Laboratoire 8 — Employee List (GraphQL)

## Authors

## Installation

1. Clone the repository and move into the project folder:

   ```bash
   git clone https://github.com/ThunderX500/LAB-8
   cd LAB-8
   ```

2. Install the client dependencies:

   ```bash
   cd client
   npm install
   ```

3. Make sure a MongoDB server is running on port 27017 (database `books-mongo`).

## Usage

- Start the GraphQL server (Spring Boot + Kotlin, port 9000):

  ```bash
  cd server
  ./gradlew bootRun
  ```

- Start the Angular development client:

  ```bash
  cd client
  npm start
  ```

- Run the client unit tests (Karma + Jasmine):

  ```bash
  cd client
  npm test
  ```

- Run the server tests (JUnit):

  ```bash
  cd server
  ./gradlew test
  ```

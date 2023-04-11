# Postgres Docker Container

This is a containerized Postgres database.

<!-- INSTALLATION -->

### Installation

1. Clone the repo

   ```sh
   git clone https://github.com/wardvisual/dockerized-db.git
   ```

<!-- Setup -->

### Setup

1. To run the container, use the following command:

   ```sh
   sudo docker compose up
   ```

2. To open a bash shell in the container, use the following command:

   ```sh
   sudo docker exec -it [container_name] bash
   ```

3. To login as posgress local account, use the following command:

   ```sh
   psql -h localhost -p 5432 -U postgres
   ```

<hr />

I hope this helps! Let me know if you have any other questions.

### Contact

Edward Fernandez: [Wardvisual](https://wardvisual.me/)

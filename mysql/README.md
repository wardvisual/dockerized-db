# MySQL Docker Container

This is a containerized MySQL database

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

3. To login as mysql root, use the following command:

   ```sh
   mysql -u root -p
   ```

4. The default password will be generated, and you will find it in the Docker logs. To update the server root password, use the following command:
   ```sh
   mysql> ALTER USER ‘root’@‘localhost’ IDENTIFIED BY [new_password]
   ```

<hr />

I hope this helps! Let me know if you have any other questions.

### Contact

Edward Fernandez: [Wardvisual](https://wardvisual.me/)

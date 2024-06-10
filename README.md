# Hello Human Application

The Hello Human Application is a simple Spring Boot application that greets users. It provides a REST API endpoint that responds with a greeting message, either a generic "Hello Human" or a personalized "Hello {name}" if a name parameter is provided.

## Endpoints

- `GET /` - Returns a greeting message. If the `name` query parameter is provided, it returns "Hello {name}". Otherwise, it returns "Hello Human".

## Example Usage

- Access the default greeting:

    ```sh
    curl http://localhost:8080/
    ```

    Response:

    ```
    Hello Human
    ```

- Access a personalized greeting:

    ```sh
    curl http://localhost:8080/?name=Razan
    ```

    Response:

    ```
    Hello Razan
    ```



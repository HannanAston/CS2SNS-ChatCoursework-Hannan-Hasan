# CS2SNS Chat Coursework – Hannan & Hasan

Description to do.

Members: 

- Abdul Hannan (240055257)

- Hasan Waheed (240184904)

## Design Diagram (Figure 1)

![design diagram](images/design-diagram.png)

## Requirements

- JDK 17 or newer (`java -version`)

## How to compile

Run from the project folder:

```
javac -d bin src\chat\common\*.java src\chat\server\*.java src\chat\client\*.java
```
Compiles server, client and common folder into the bin directory.

## How to run

Start the server first:

```
java -cp bin chat.server.ChatServer
```

Then start a client in a new terminal. Repeat for each extra user:

```
java -cp bin chat.client.ChatClient
```

The server listens on TCP port 5000. Press `Ctrl+C` to stop either program.

## How we work

- `main` always compiles and runs.
- to be noted

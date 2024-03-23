#   Cargo commands
-   To create this project
    ```
    cargo new hello_cargo
    ```
-   To build project
    This command creates an executable file in target/debug/hello_cargo rather than in your current directory. Because the default build is a debug build, Cargo puts he binary in a directory named debug.
    ```
    cargo build 
    ```
-   we can also use cargo run to compile the code and then run the resultant executable all in one command
    ```
    cargo run
    ```
-   Cargo also provides a command called  cargo check . This command quickly checks your code to make sure it compiles but doesn’t produce an executable
    ```
    cargo end
    ```
-   ou can use  cargo build --release  to compile it with optimizations. This command will create an executable in target/release instead of target/debug.
    ```
    cargo build --release
    ```
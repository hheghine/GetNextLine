# Get Next Line (GNL)

The **Get Next Line (GNL)** project involves coding a function that reads a line ending with a newline from a file descriptor. This project not only introduces a convenient function to your toolkit but also provides insight into the concept of "static variables" in C programming.

> :warning: **Note:** Understand all code before using it; copying without comprehension is detrimental.

## About the Project

### Function Prototype

```c
char *get_next_line(int fd);
```

Your program should be compiled with the `-D BUFFER_SIZE=xx` flag, where `xx` is the buffer size for the read calls within your `get_next_line` function.

Ensure that your function performs well both when reading from a file and when reading from the standard input.

## How It Works

The `get_next_line` function is designed to read a single line ending with a newline character (`\n`) from a file descriptor (`fd`).

The key feature of `get_next_line` is its ability to manage static variables. These variables retain their values between function calls, allowing the function to keep track of the state of reading between calls. This is particularly important when reading lines that span multiple buffer reads.

## Conclusion

The **Get Next Line** project offers an opportunity to develop a function that reads lines from file descriptors while effectively handling static variables. This knowledge is highly valuable for managing input/output operations in C programming.

<img width="149" alt="image" src="https://user-images.githubusercontent.com/119530584/224476043-437dd322-3fdd-4025-aaaf-22d7d2ee835c.png">

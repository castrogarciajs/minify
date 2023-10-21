# Welcome to the Fetchy

<img align="right" src="./ferry.png" height="150px" alt="the rust mascot">


The **Fetchy** is a command-line tool developed in Rust that empowers users to seamlessly interact with RESTful APIs from their terminal. Whether you're fetching data, posting information, or managing API resources, this CLI tool simplifies the process by offering a straightforward and intuitive interface.


## Key Features

- **Easy Configuration:** Configure the base URL, authentication, and custom headers for your API requests.
- **HTTP Methods:** Supports various HTTP methods, including GET, POST, PUT, DELETE, and more.
- **Testing and Documentation:** Write tests to ensure functionality and provide detailed documentation for users.

## Example

Init config for fetchy

```sh
fetchy --config init
```

```log
Created file successfuly!
```

command: 
```sh
fetchy --method get --url /languagues
```

response:

```log
[
  {
    "name": "Java",
    "publish_date": "1995",
    "description": "Java is a widely used programming language that is designed to be platform-independent."
  },
  {
    "name": "C++",
    "publish_date": "1985",
    "description": "C++ is a general-purpose programming language that supports object-oriented programming."
  },
  {
    "name": "Python",
    "publish_date": "1991",
    "description": "Python is a high-level programming language known for its simplicity and readability."
  },
  {
    "name": "C#",
    "publish_date": "2000",
    "description": "C# is a modern programming language developed by Microsoft for building a variety of applications."
  },
  {
    "name": "Ruby",
    "publish_date": "1995",
    "description": "Ruby is a dynamic, object-oriented programming language known for its simplicity and productivity."
  }
]
```

## Install
Shell (Mac, Linux) - **Unstable**

Soon...

## License

This project is LICENSE **MIT**.


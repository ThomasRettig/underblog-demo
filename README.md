# Underblog Demo
This is a simple boilerplate template for [Underblog](https://github.com/freetonik/underblog), a simple static site generator written in Go.

## Running locally
1. Make sure that Underblog is successfully installed on your machine. Download the appropriate binary from the [Github repo](https://github.com/freetonik/underblog/releases/tag/v0.2.3), and then add the folder containing the `.exe` to PATH.

2. From the root of the project directory, run the following:

```bash
$ underblog -watch
```

A localhost server will start at https://localhost:8080/. Underblog watches for file changes and will automatically rebuild the HTML.

### License
The code in this repository is MIT licensed.

# Quick Start

Build:
```sh
sudo docker build -t gin-builder .
```

Run:
```sh
sudo docker run -it -p 8888:8888 gin-builder
```

Run and mount config.ini:
```sh
sudo docker run -v /path_to_folder/config.ini:/opt/config.ini ollama-test
```

Jupyter will be available at http://localhost:8888

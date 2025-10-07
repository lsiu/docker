# My qwen-code docker

My qwen-code docker build with:
* python to run juypter notebooks

## How to run
```sh
docker run --rm -it --mount type=bind,source=.,target=/code-root --mount type=bind,source=.qwen,target=/root/.qwen lsiu/qwen-code:latest sh -c "cd /code-root && qwen"
```

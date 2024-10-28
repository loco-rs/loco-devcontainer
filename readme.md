# Loco.rs devcontainer for VSCode

`loco-devcontainer` is a simple configuration to support fully-dockerised development of Loco applications using Visual Studio Code.


## Quick Start


You can download the files in this repo and place them in the special `.devcontainer` folder in your Loco app. 

Alternatively, you may use [Git Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules):


```sh
git submodule add https://github.com/loco-rs/loco-devcontainer .devcontainer
```

If you use this method, do not forget to install submodules when cloning:

```
git clone --recurse-submodules ...
```

#### Usage

Be sure to review the various components we have set up for you in [compose.yaml](./compose.yaml), and the base Docker image in [Dockerfile](./Dockerfile).

To see how everything connects with your app, look at the [.env](./.env) environment variables set up.


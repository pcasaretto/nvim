# nvim in a container

I'm currently experimenting with isolating everything inside a container.
This is my attempt to encapsulate my flavor of vim, the plugins and the configs I dig.

# Usage

```shell
alias edit='docker run --rm -it -v $PWD:/data pcasaretto/nvim'
```

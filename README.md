# Tmux config

## Installation 

``` bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

``` bash
brew install sesh
```

## Mappings 

I like my point to be on `j`, a lot. 

So hjkl -> jkl;

> [!NOTE]
> Make sure that the terminal is sending the right keycode when you press
> ctrl+;. Here is how to do it in kitty:
>
> ``` kitty
> map ctrl+semicolon send_text all \x1b[59;5u
> ```
>
> Microsoft Terminal:
>``` json
>{
>    "id": "User.sendInput.AC260877",
>    "keys": "ctrl+vk(186)"
>}
>  ```
>

## Important ones to remember

Prefix + $: rename session 
Prefix + ,: rename window 
Prefix + w: list sessions
Prefix + c: create new tab
Prefix + t: list tmux session to connect to 

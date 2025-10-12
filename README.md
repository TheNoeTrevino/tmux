# Tmux config

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

## Important ones to remember

Prefix + $: rename session 
Prefix + ,: rename window 
Prefix + w: list sessions
Prefix + c: create new tab
Prefix + T: list tmux session to connect to 

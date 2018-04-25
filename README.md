# bashrainbow
Print random colors on your terminal

## Installation
```bash
curl https://raw.githubusercontent.com/AlexBaranowski/bashrainbow/master/rainbow | sudo tee /usr/bin/rainbow
chmod 755 /usr/bin/rainbow
```
## Usage
```bash
rainbow # prints random colors once
rainbow -c 2 # prints random colors twice
rainbow -i # prints random colors infinietely
rainbow -s 0 -c 2  # prints random colors twice with 0 sleep time between each print
rainbow -i -s 0 -c 2 # prints random colors infinietely with 0 sleep time between each print


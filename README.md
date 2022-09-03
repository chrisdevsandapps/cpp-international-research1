

# C++ International Research


github: https://github.com/chrisdevsandapps/xxx

dir: /Users/wow/Documents/cpp/cpp-international-research

### notes:
1. `md1-xxx.md` <--- markdownFiles
1. `./tXyz` <--- directory with topics
1. zzz


<br> <br> <br>


### compiling in terminal:

```sh

g++ helloworld.cpp -o ./binOutput/hello

./binOutput/hello

```


<br> <br> <br>


### using makefile
```makefile

VAR1 = helloworld
VAR2 = hello



love: $(VAR1).cpp
	g++ $(VAR1).cpp -o ./binOutput/$(VAR2)
	sleep 1
	echo "hello world! hahaha!"
	sleep 1
	clear
	./binOutput/$(VAR2)

clear:
	rm ./binOutput/$(VAR2)
    
```


<br> <br> <br>


### local project vscode settings
`.vscode/settings.json

```json
{
    "git.enabled": false,
}
```


<br> <br> <br>

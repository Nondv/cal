# cal

I was dissapointed by default Mac OS `cal` utility because it
showed calendar without highlighting and from sunday so
I wrote this script to replace it.

Some months after that I found it and decided to refactor and improve it.
Here it goes.


## Usage

I've created `~/bin` directory, added it to PATH and place script in it.
Like this:

```bash
mkdir `~/bin`
cp cal ~/bin
```

in `.bashrc`:

```
PATH="/Users/nondv/bin:${PATH}"
export PATH
```

Here it is. Try it: `cal -h`

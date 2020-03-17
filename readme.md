pip install playsound

After install the problem arise that, `ModuleNotFoundError: No module named 'gi'`

To solve this problem follow this instruction,

```

pip install vext

pip install vext.gi

sudo apt-get install pkg-config libcairo2-dev gcc python3-dev libgirepository1.0-dev

pip install gobject PyGObject

```
this issue solve.


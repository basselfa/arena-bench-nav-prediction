## Simple Installation

Clone repo in any catkin ws or create new catkin ws

```
git clone git@github.com:Arena-Rosnav/arena-rosnav.git
```

Change into dir

```
cd arena-rosnav
```

Ros install

```
rosws update
```

Install python pkgs, you need poetry for this

```
poetry shell && poetry install
```

Install stable baselines

```
cd ../forks/stable-baselines3 && pip install -e .
```

Build catkin

```
cd ../../.. && catkin_make
```

Finished!

#### TODO

Everything

Documents:
- https://drive.google.com/drive/folders/1q8LasUSgNhUToUv81zGGmYFGJ5b3cHQB?usp=sharing

Important Links:
- https://arena-benchmark.readthedocs.io/en/latest/
- https://github.com/Arena-Rosnav

TU Drive
- https://tubcloud.tu-berlin.de/s/M9NYDab8rNmW6fo

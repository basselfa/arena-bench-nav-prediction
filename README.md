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

Project Documents:
https://drive.google.com/drive/folders/1q8LasUSgNhUToUv81zGGmYFGJ5b3cHQB?usp=sharing

Project Protocol:
https://docs.google.com/spreadsheets/d/1omRDyfzvQiBUo7YHfzZQpq2DSHT6rZO12xTt2y4HpB0/edit#gid=0

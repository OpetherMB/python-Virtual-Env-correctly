
# creation de l'env virtuel "mon_env" (dans le répertoire mon_env)
```
python3 -m venv mon_env
```
# on rentre dans l'env
```
source mon_env/bin/activate
```

C'est mieux d'utiliser cette maniere que plutot d'utilisé le pip pour evité les conflit, comme ca on est sur 100% qu'on est entrain d'utilisé le python de l'env 

comme mésure de sécurité faut tjrs verifier quel python avec ` which python`

# installation de pandas et de ses dépendances dans l'env "mon_env"
```
python3 -m pip install pandas
python3 -m pip install scikit-learn
```
or mieux 

```python -m pip install -r requirement.txt```

```
(mon_env) root@xxxx.xxxxxx [vs1]:~/tmp # python3
Python 3.5.3 (default, Apr 5 2021, 09:00:41)
[GCC 6.3.0 20170516] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import pandas
>>> import sklearn
```


# pour sortir de l'env 
deactivate

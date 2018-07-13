pipenv-speed-test
===================

Example of a pipenv run. Doing a `pipenv sync -d` or `pipenv install -d` yield slow
times

Example
-------

Running on OSX, brew installed pipenv 2018-7-1, here is an example:

```
pipenv-slow-example]$ time pipenv sync -d
Installing dependencies from Pipfile.lock (d4212a)...
  🐍   ▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉ 51/51 — 00:00:11
To activate this project's virtualenv, run pipenv shell.
Alternatively, run a command inside the virtualenv with pipenv run.
All dependencies are now up-to-date!

real	0m12.391s
user	0m32.920s
sys	    0m5.074s
```

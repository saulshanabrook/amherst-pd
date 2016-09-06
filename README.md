# Amherst Police Department Data

Extracting useful information from data from the Amherst, MA police department.

We try to understand how:

* How police response changes based on race and gender of suspects.
* Where, geographically, police spend most of their time.
* How these have changed over time.

Inspired by the Justice Department's report on the Baltimore Police Department.

## Playing

```bash
docker run  -p 8888:8888 -v $(pwd):/home/jovyan/work  jupyter/scipy-notebook
```

## Data

All data requests form Amherst PD records department. Currently just looking at
summary stats of gender, race, by year. Haven't analyzed PDF arrest logs yet.
Hoping to get them in an easier format.

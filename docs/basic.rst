
Introduction
============

Basic Usage
-----------

Opening a data file
*******************

Currently these need to be sqlite databases, but we will switch also support
CSV files.

```
data = niimpy.open('datafile.sql')
```

This loads the data and creates a niimpy data object. We can list the subjects
in the datafile using

```
data = data.users()
```

The `tables`-method returns a list of the measurements in the data

```
data = data.tables()
```

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

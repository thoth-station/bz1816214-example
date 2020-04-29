# bugzilla 1816214

Run tensorflow on RHEL image

1. Install micropipenv

.. code-block:: console

    pip3 install micropipenv --user

2. Create environment.

.. code-block:: console

    python3 -m venv venv/ && . venv/bin/activate

2. Install software stack.

.. code-block:: console

    micropipenv install --deploy

3. Run command within the environment

.. code-block:: console

    ipython

    Python 3.6.10 (default, Dec 20 2019, 00:00:00) 
    Type 'copyright', 'credits' or 'license' for more information
    IPython 7.13.0 -- An enhanced Interactive Python. Type '?' for help.

4. Import tensorflow

.. code-block:: console

    In [1]: import tensorflow as tf

    In [2]: tf.version  
    Out[2]: <module 'tensorflow_core._api.v2.version' from '/home/fmurdaca/.local/share/virtualenvs/bz1816214-example-HUsuhuZU/lib/python3.6/site-packages/tensorflow_core/_api/v2/version/__init__.py'>

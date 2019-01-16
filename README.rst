Setup
=====

Do the following commands in powershell after installing
python3.7 on your system.

.. code:: powershell

    cd \u
    git clone https://github.com/directbuy/bigcommerce_elastic
    cd \u\bigcommerce_elastic
    python3.7 -m venv .
    source bin/activate
    pip install -r requirements.txt


Running
=======

Use the following in powershell to run the notebook.

.. code:: powershell

    cd \u\bigcommerce_elastic
    source bin/activate
    ipython --notebook

vist http://127.0.0.1:8888 in your browser and begin hacking away.

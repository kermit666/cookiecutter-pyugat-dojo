Cookiecutter template for the [PyUGAT Coding Dojo](http://pyug.at/PythonDojo).

Requirements:

    $ pip install cookiecutter

Usage:

    $ cookiecutter gh:kermit666/cookiecutter-pyugat-dojo
    Cloning into 'cookiecutter-pyugat-dojo'...
    remote: Counting objects: 10, done.
    remote: Compressing objects: 100% (8/8), done.
    remote: Total 10 (delta 2), reused 10 (delta 2), pack-reused 0
    Unpacking objects: 100% (10/10), done.
    Checking connectivity... done.
    exercise_name (default is "FizzBuzz")? RomaniIteDomum
    exercise_module (default is "fizzbuzz")? romans
    $ cd RomaniIteDomum
    $ pip install -r requirements.txt
    Requirement already satisfied (use --upgrade to upgrade): nose
    Requirement already satisfied (use --upgrade to upgrade): yanc
    Requirement already satisfied (use --upgrade to upgrade): nosy
    $ nosy
    .
    ----------------------------------------------------------------------
    Ran 1 test in 0.002s

    OK

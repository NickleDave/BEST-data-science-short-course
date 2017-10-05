We will be using Anaconda, an open platform for data science that makes
it much easier to install scientific computing libraries used with
Python, R, and other languages.

**Please install Anaconda with the current version of Python, 3.6**
* Windows: https://repo.continuum.io/archive/Anaconda3-4.3.0.1-Windows-x86_64.exe
* OSX (Mac): https://repo.continuum.io/archive/Anaconda3-4.3.0-MacOSX-x86_64.pkg
* Linux: https://repo.continuum.io/archive/Anaconda3-4.3.0-Linux-x86_64.sh

Okay, you should be ready! All the scientific packages
you need come installed already with Anaconda.

### If you already had Anaconda installed *before* taking this short course:
**You don't have to install a newer version. Just make sure you have a
conda environment that uses some version of Python 3.** I will explain
what an environment is in class.

Like so
(*you don't have to type the `$` or `>` at the beginning of the lines below,
those are just to indicate the prompt when you're using the command line*)

1. Open up an Anaconda terminal and type

  `> conda create -n bootcamp python=3.5`

  (then hit `Enter`)

2. Then do

  (Mac/Linux)
  `$ source activate short-course`

  (Windows)
  `> activate short-course`

3. Your command line prompt should now look something like this:
  `(short-course) >`.

   You're going to install required packages into the environment you've
    just created. (I'll explain what that means in class.)

   To install those packages, enter the command

  `> conda install jupyter pandas numpy pip`

  and say `y` when it asks you whether it's okay to install the
  dependencies (trust me, it's okay)

To deactivate you just enter `deactivate` (for Windows) or
`source deactivate` (for Mac), or simply close the terminal.

You'll want to open an Anaconda terminal and activate that conda
environment again when we start using the Jupyter notebooks in the
 short course.

                                Assignment - 2
                                (Manish Malik - mmalik44)
The code for this assignment was derived from the work done by previous semester student Chad Maron (link to his
repository https://github.com/cmaron/CS-7641-assignments), his work is derived from the work done by JonathanTay (link
to his repository: https://github.com/JonathanTay/CS-7641-assignment-2) which is actually using the awesome library published
Pushkar named ABAGAIL (https://github.com/pushkar/ABAGAIL).

In order to run my project please download the project from https://github.com/manishmalik/CS-7641-assignments/tree/master/assignment2
and then follow the following step:
1. Please download jython and python 3 on your system. I ran my project on jython 2.7.1 on MacBook Pro. So, please download
the same version.
2. Create a python virtual env. And run pip install -r requirements.txt file to download all the helper files.
3. Now first split the data into test, train and validation set. You may do that using :
`python run_experiment.py --seed 1234 --dump_data`
4. Once you did that you will observe the data in the data/ folder.
5. To run the experiments follow these steps:
    5.1 For part 1, you should run the following program: (but before you do that make sure that base.py should
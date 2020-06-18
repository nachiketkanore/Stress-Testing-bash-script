# Stress Testing bash script

In competitive programming, stress testing is a technique of testing your solution on a number
of random test cases to find where the code might fail. 

### Installing
Download this repository manually or by using git clone on terminal.

Copy your original solution which you expect might fail in the file `solution.cpp`. <br>
Copy your brute force solution which is expected to give correct output in the file `brute.cpp`. <br>
Change the `gen.cpp` file so as to generate test cases according to the question. <br>

Now open your terminal in the directory where file `s.sh` resides and execute:<br>
Once give the execute permissions to `s.sh` file using: <br>
$ `sudo chmod +x s.sh` <br>
and then execute: <br>
$ `bash s.sh` to run the script.

Output:<br> the output of running file `s.sh` on every test case is either `Accepted` if your solution's output matches the brute solution output or `Wrong Answer` and will show the input on which the solution failed, the output of your solution and expected output according to the brute force solution on terminal and the script will be terminated. Now you can debug your original solution and check where it goes wrong. <br>
If you wish to terminate the script at any moment you wish use the command `ctrl + c` in your terminal.

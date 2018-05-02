# tools

## test\_shell
modify `test_yours.sh`,for example:
```bash
python helloworld.py
```
then 
```bash
./start_from_here.sh 3 /home/username pre
```

* `3` means the repeating times
* `/home/username` meas the directory where you want to put your logs
* `pre` meas the logs prefix

finally, you will get `3` files in `/home/username` as follows:
```bash
username@ubuntu:ls
pre_test_yours_0.txt
pre_test_yours_1.txt
pre_test_yours_2.txt
repeat_test.out
```

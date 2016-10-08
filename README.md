# describe what each script is doing
0: "echo" is the linux command that will print [display]. "Hello world" is the string that needs to be printed.<br>
1: Between grep and echo, not sure yet so I will have to revisit as I keep getting "unexpected EOF"<br>
2: "cat" is the linux command that prints out the content of the file, followed by the name of the file you want to display.<br>
3: "cat" is the linux command that prints out the content of the file, followed by the name of the file you want to display. In this case, we want to display two of them, so we write out both of them.<br>
4: Dora's tip was most helpful (also helped me know I was on the right track for the previous "display text" exercises). "tail" is the linux command that prints out the last 10 lines of the file.<br>
5: "head" is the linux command that prints out the first 10 lines of the file we want to display.<br>
6: "head" outputs the first part of the file, with the third line specified with "-n 3". "tail -n 1" specifies that only one line should print out to display.<br>
7: This has to do with 1, which I am not sure about but I think my Synopsis is in the right direction.<br>
8: "ls -la" will take the contents of its own output and append it to the file "ls_cwd_content". Since the file doesn't even exist, it will be created (unsure if you can use ">" to do this as well).<br>
9: We want to duplicate the last line, so we need to use "tail". Being it's the last line (we want to duplicate), we need to use "-n 1". Lastly, we need to name the file we want this script to execute on (to duplicate the last line).<br>
10: I went down the pipeline route, but Ian saw my initial script and brought to my attention that "rm" can be done within "find"

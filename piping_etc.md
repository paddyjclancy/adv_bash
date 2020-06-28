# ps (process status) command
Used to provide information about the currently running processes, including their process identification numbers (PIDs).

# ps -aux command
Shows all processes for all users

# Pipes & redirection
Pipes allow you to combine commands one after the other, like a pipeline.

`|` is the 'pipe' command


`ls -1` gives a 1 column list

`less` program which lets you see output one screen at a time


`ls -1 | less` ==> output of `ls -1` = input to `less`

# Create a process and kill it

The `&` makes the command run in the background.
  ```
  sleep 50 &
  ```
  This will make the machine sleep for 50 seconds it return a process id

  ```
  kill process_id
  ```
  This kills the process


  Fahad Khisaf

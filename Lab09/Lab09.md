## Lab 09

- Name: Donnell Smith
- Email: smith.2883@wright.edu

## Part 1 Answers

- Make sure infinity is in your Lab09 folder in GitHub

## Part 2 Answers

1. Getting started
   - Command to find the PID: ps
   - PID of "Terminal A": 1603(ps)
   - PID of "Terminal B": 6675(ps)
2. Using `./` to run `infinity` in Terminal B
   - PID of script: 6746(ps)
   - Command to kill script: kill -9 <6746>
   - Effects of running the script: Yes, you can still use the Terminal if you run the script
3. Using `source` to run `infinity` in Terminal B
   - PID of script: 6834(ps)
   - Command to kill the script: kill -9 <6834>
   - Effects of killing the script: if you kill the correct PID it kills all operations
4. Running `infinity` as a background job in Terminal B
   - Command to run script in background: source infinity.ssh
   - Job ID of script: 6645(bash) 
   - PID of script: 6887(ps)
   - Command to kill script via job id: kill <6645>
   - Effects of exiting terminal: if you exit from the terminal window, you kill any processes you started
5. Run `infinity` in a `screen` or `tmux` session
   - Command(s) to run `infinity` in a screen session: source infinity.ssh
   - Detach from `screen` / `tmux` session: Ctrl + B then press D (press Ctrl+B let go then press D)
   - Command to show `screen` / `tmux` sessions: Ctrl + A then press " (press Ctrl+A let go then press ")
   - Effects of exiting terminal: 
   - Command / steps to kill the `screen` / `tmux` session: To kill when attached Ctrl + B and X (To kill otherwise Ctrl + B and Y)

## Part 3 Answers

1.
2.
3.
4.
5. Confirmed?
6.
7.
8.
9. Confirmed?
10.

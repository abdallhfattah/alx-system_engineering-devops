# 0x05. Processes and signals

This project contains several Bash scripts that demonstrate how to work with processes and signals in Unix/Linux environments.

## Scripts Description

1. **0-what-is-my-pid:** Displays the PID of the script itself.

2. **1-list_your_processes:** Displays a list of currently running processes, including process hierarchy and all users, even those without a TTY.

3. **2-show_your_bash_pid:** Displays lines containing the word "bash," allowing you to easily get the PID of your Bash process.

4. **3-show_your_bash_pid_made_easy:** Displays the PID and process name of processes whose name contains the word "bash."

5. **4-to_infinity_and_beyond:** Displays "To infinity and beyond" indefinitely, with a 2-second sleep between each iteration.

6. **5-dont_stop_me_now:** Stops the 4-to_infinity_and_beyond process.

7. **6-stop_me_if_you_can:** Stops the 4-to_infinity_and_beyond process without using `kill` or `killall`.

8. **7-highlander:** Displays "To infinity and beyond" indefinitely, with a 2-second sleep between each iteration. Displays "I am invincible!!!" when receiving a SIGTERM signal.

9. **67-stop_me_if_you_can:** Kills the 7-highlander process instead of the 4-to_infinity_and_beyond one.

10. **8-beheaded_process:** Kills the 7-highlander process.

## Requirements

- These scripts are intended to be run on Unix/Linux systems.
- Some scripts may require execution permission (`chmod +x script_name.sh`).

## Usage

1. Clone the repository:
```git clone https://github.com/your_username/alx-system_engineering-devops.git```

2. Change directory to the project folder:
```cd alx-system_engineering-devops/0x05-processes_and_signals```

3. Run any script using Bash:
```./script_name.sh```

## Author

Abdallah Yassin

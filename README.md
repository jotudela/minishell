# 🚀 INTRODUCTION

The `minishell` project at 42 school immerses students in the dynamic world of UNIX shell development within the C language. This comprehensive undertaking requires a deep understanding of system calls, process management, and parsing techniques.

Students are tasked with crafting a minimalistic shell that mimics the fundamental functionalities of a UNIX command-line interface.

Beyond basic command execution, minishell delves into advanced features such as environment variable handling, signal management, and piping. Leveraging knowledge in lexical analysis and parsing, students navigate the intricacies of command interpretation and user interaction.

This project, interwoven with the philosophy of simplicity and efficiency, not only sharpens skills in system-level programming but also imparts a practical understanding of the core components that constitute a fully functional shell.

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# 🛠️ Program Specificities and Considerations

Start by clonning my repo :
```bash
git clone git@github.com:jotudela/minishell.git && cd minishell
```

> [!IMPORTANT]
> The program must replicate the behavior of a shell in interactive and non-interactive modes, following the project’s strict guidelines.

> [!NOTE]
> Undefined behavior, such as unclosed quotes or incorrect handling of special characters, should be avoided.

The program should :
- Display a prompt when waiting for user input.
- Execute commands found in the PATH or using absolute/relative paths.
- Handle errors gracefully and display appropriate messages.
- Implement built-in commands as specified in the subject.

## ⚙️ Usage

To execute my program wich is called `minishell`, compile it using :
```bash
make
```

It run like that :
```bash
./minishell
```

As long as the program is running, it display a prompt to invite the user write a command.
Example :
```bash
/Users/user/docs/minishell
💻 ls -l
```

output :
```bash
total 8
-rw-r--r-- 1 user user 1024 Jan 15 2025 file1.txt
-rw-r--r-- 1 user user 2048 Jan 15 2025 file2.txt
```

My final grade :

![](imgs/101_percent.png)

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🤝 Contribution
Contributions are open, make a pull request or open an issue 🚀

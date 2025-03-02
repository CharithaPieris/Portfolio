# Running commands in the shell

PowerShell is a command-line shell and a scripting language used for automation. Similar to other
shells, like `bash` on Linux or the Windows Command Shell (`cmd.exe`), PowerShell lets you to run
any command available on your system, not just PowerShell commands.

## Types of commands

For any shell in any operating system there are three types of commands:

- **Shell language keywords** are part of the shell's scripting language.

  - Examples of `bash` keywords include: `if`, `then`, `else`, `elif`, and `fi`.
  - Examples of `cmd.exe` keywords include: `dir`, `copy`, `move`, `if`, and `echo`.
  - Examples of PowerShell keywords include: `for`, `foreach`, `try`, `catch`, and `trap`.

  Shell language keywords can only be used within the runtime environment of the shell. There is no
  executable file, external to the shell, that provides the keyword's functionality.

- **OS-native commands** are executable files installed in the operating system. The executables can
  be run from any command-line shell, like PowerShell. This includes script files that may require
  other shells to work properly. For example, if you run a Windows batch script (`.cmd` file) in
  PowerShell, PowerShell runs `cmd.exe` and passes in the batch file for execution.

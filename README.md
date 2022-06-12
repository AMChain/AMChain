# AMChain

> Blockchain for registering interactions

For more information see: https://github.com/AMChain/AMChain

AMChain это и название программы (в этом репозитории реализация на Python3)
и название протокола

## Usage

```
  app_name [<flags>] <command> [<arg>] ...

SUBCOMMANDS
  BASIC COMMANDS
    basic             Запуск в basic режиме
    ip  <port> <name> Запуск в сокет

  ПРОТОКОЛЬНЫЕ ЗАПРОСЫ
    GET   запросы из децентрализованной сети
    VZM   регистрация записи взаимодействия

  NETWORK COMMANDS
    id            Show info
    diag          Print diagnostics

  TOOL COMMANDS
    config        Manage configuration
    version       Show amctl version information
    commands      List all available commands

  Use 'app_name help <command> ' to learn more about each command.

  AMChain размещает свои файлы на системном диске
  В этой версии будет размещаться в папке ~/.amc
  
  To change the repo location, set the $AMСPATH environment variable:

  bash: export AMCPATH=/path/to/repo
  fish: set -gx AMCPATH "/path/to/repo"
```

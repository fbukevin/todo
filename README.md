

A command-line todo list for practice.

## Usage

```bash
Usage:
  todo task
  todo book
  todo task add <name>
  todo book add <name>
  todo task rm [<name> | (-n | --no) <number>]
  todo book rm [<name> | (-n | --no) <number>]
  todo task find <number>
  todo book find <number>
  todo task WIP <number>
  todo task DONE <number>
  todo book PENDING <number>
  todo book WIP <number>
  todo book DONE <number>
  todo book PENDING <number>
  todo task update <number> <content>
  todo book update <number> <content>
  todo (-h | --help)
  todo --version
```  

## References

* Command line arguments parser and prompt: https://docs.python.org/2/library/argparse.html
* Sqlite3 module and tutorial: http://www.runoob.com/sqlite/sqlite-python.html

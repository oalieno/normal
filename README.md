# normal

Just a normal tool, nothing special...

Help you manage your password through a master key with AES encryption

## Usage

```
Usage:
  ./normal.py add <value> [-f FILE] [-gl VALUE]
  ./normal.py list [-df FILE]
  ./normal.py query <value> [-i VALUE] [-df FILE]
  ./normal.py delete <value> [-i VALUE] [-f FILE]
  ./normal.py generate [-l VALUE]

Options:
  -h --help                Show this screen
  -f FILE --file=FILE      Specify password file [default: {}]
  -d --decrypt             Decrypt secret detail [default: False]
  -g --generate            Generate password [default: False]
  -i VALUE --index VALUE   Specify entry index [default: -1]
  -l VALUE --length VALUE  Password length [default: 16]
```

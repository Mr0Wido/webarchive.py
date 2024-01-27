# webarchive.py
This Python script is used to extract URLs from the https://web.archive.org. It can be used to specify a single domain or a list of domains from which URLs will be extracted.

### Installation

```
git clone https://github.com/Mr0Wido/webarchive.py.git
cd webarchive.py
python3 webarchive.py
```

### Usage

```
python3 webarchive.py -d example.com
python3 webarchive.py -d example.com -o result.txt
python3 webarchive.py -l example.txt
```

### Options
**Flags** |    | Description
---| --- | ---
-h | --help | Show this help message and exit.
-d | --domain | Domain name.
-o | --output | Output file to save urls.
-l | --list | Domain list file.

### Requirments

```
argparse
requests
json
```

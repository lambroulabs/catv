# catv
copy file contents to clipboard with basic syntax

General Usage: 
```bash
catv <filename>
```


Advanced Usage: 
```bash
catv [--force-binary|-f] [--b64|-b] [--force-text|-t] <filename>
```

**binary**: copy file _object_

**text**: copy file _text contents_

**b64**: convert _file contents_ to _base 64_ encoding

## You cannot use binary and text at the same time.

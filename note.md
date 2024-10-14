
linux build:
```bash

```
测试指纹智能扫描功能

```bash
./nuclei -u http://127.0.0.1:1234 -t ~/nuclei-templates -id dir-listing -duc -as -max-host-error 1000     
```

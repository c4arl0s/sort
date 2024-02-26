# sort

sort – sort or merge records (lines) of text and binary files

file.txt

```console
362130
637216
632163
859485
057328
637213
647326
632163
057328
536215
536215
467326
785437
```

```console
file.txt sort
```

Output console

```console
057328
057328
362130
467326
536215
536215
632163
632163
637213
637216
647326
785437
859485
```

```console
-u, --unique
             Unique keys.  Suppress all lines that have a key that is equal to an already processed one.  This option, similarly to -s, implies a
             stable sort.  If used with -c or -C, sort also checks that there are no lines with duplicate keys.
```

Executing with u flag

```console
sort -u file.txt
```

```console
057328
362130
467326
536215
632163
637213
637216
647326
785437
859485
```

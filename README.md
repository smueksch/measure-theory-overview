# Measure Theory - Overview Sheet

This repository includes an overview sheet with condensed definitions, theorems and observations from a course in basic measure theory and probability.

If you are unfamiliar with the ```git``` family of commands, you can simply download a ```.zip``` archive of this repository using the green button above.

## Compilation Issues

This project makes use of the ```\input{}``` command to make the ```.tex``` files more readable and easier to maintain. In case there is any issue compiling this project on your system, check the ```\input{}``` commands in the ```main.tex``` file, there may be an issue with the declaration of the path. Specifically, this project uses relative paths in the following way:

```
\input{chapters/basic-notions}
```

You may need to adjust the paths for your system, which may involve changing the ```/``` to something appropriate.

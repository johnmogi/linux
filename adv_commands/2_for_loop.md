#!/bin/bash

for i in $(ls) ; do
    echo $i
done

for i in $(find / -name passwd) ; do
    echo $i
done

for i in `ls` ; do echo $i ; done

for i in $( find / -name passwd ) ; do
    echo $i
done

for i in `find / -name passwd` ; do echo $i ; done

// chmod +x .script.sh
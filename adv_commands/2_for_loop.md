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

for count in `seq 1 10` ; do echo $count ; done


// chmod +x .script.sh
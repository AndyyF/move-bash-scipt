# move-bash-script

This is a Linux script in order to move a file:

- which is in a certain directory
- named "\*plot" and "plot\*"
- file-size above 101Gb




## Explanation
```
find ~/dir_source -size +101G -name "*plot" -name "plot*" -exec mv -nv {} ~/dir_destination \;
```
This line is looking for the named parameters and moves the found file to the destination.

```
echo "checked at:      $(date)"
```
Prints out the current Time


```
sleep 20m
```
sleeps for 20 minits

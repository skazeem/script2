# script2
#!/bin/bash
echo -e "enter file/directory name : \c"
read fn
if [ -d "$fn" ]; then
ls $fn
elif [ -f = "$fn" ]; then
more $fn
else
      echo "invalid"
fi

# script2
#!/bin/bash
read $filename
if [ -d "$filename" ]; then
      echo "ls $filename"
elif [ -f "$filename" ]; then
       echo "more $filename"
else
      echo "invalid"
fi

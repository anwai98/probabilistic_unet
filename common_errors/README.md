1. `/usr/lib64/libstdc++.so.6: version 'GLIBCXX_3.4.21' not found` </br>
Solution : https://stackoverflow.com/questions/58424974/anaconda-importerror-usr-lib64-libstdc-so-6-version-glibcxx-3-4-21-not-fo </br>

`export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/scratch/users/archit/mambaforge/lib` - This worked for me!

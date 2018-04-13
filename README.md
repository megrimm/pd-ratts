# pd-ratts

on MacOS

$ ./autogen.sh
$ ./configure --with-pd-include=/Applications/Pd.app/Contents/Resources/src/ --prefix=$HOME/Documents/Pd/externals/
$ make

make install will install externals to ~/Documents/Pd/externals/pd/externs .... so that need to be fixed with ./configure
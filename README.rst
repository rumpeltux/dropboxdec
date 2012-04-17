Dropbox Bytecode Decryption Tool
================================

| Copyright Hagen Fritsch, 2012, License: GPL-2.0
| _marshal.py adpoted from pypy (MIT License)

See http://itooktheredpill.dyndns.org/2012/dropbox-decrypt for further information.

How to use
----------

Grab and unpack the prerequisites::

    wget -nv https://github.com/rumpeltux/dropboxdec/tarball/master -O - | tar xzv
    wget -nv http://dl-web.dropbox.com/u/17/dropbox-lnx.x86-1.1.45.tar.gz -O - | tar xzv
    cd .dropbox-dist; unzip library.zip; chmod a+rw -R .; cd ..

Run the decryption tool::

    python dropboxdec*/dec.py .dropbox-dist

It raises an error for an unknown opcode in netifaces.pyc, but that's ok (and you can always download the netifaces library source).
Now feel free to do st. cool with it :)

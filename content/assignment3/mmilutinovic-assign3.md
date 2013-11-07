Title: PeerLibrary project update
Date: 2013-10-18 06:06
Category: assignment3
Tags: peerlibrary
Slug: mmilutinovic-assign3
Author: Mitar

[PeerLibrary](http://peerlibrary.org) development has been progressing steadily. The last major feature added is a package named [PeerDB](https://github.com/peerlibrary/meteor-peerdb) which aims to bring support for easy collaborative database around MongoDB. The idea is that a developer does not have to think about all the aspects needed for implementing a database which can support collaborative process, but designs the database so that it works for one user, but then PeerDB layer extends this for use by multiple users editing the same object. For this PeerDB makes sure all references between documents are properly kept in sync and (not yet implemented) that no state of the document is lost, but all versions are stored to be possibly reviewed by community, restored, or just viewed.


added Comments Thomas 11/6/2013 (see commit description)

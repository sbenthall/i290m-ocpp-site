Title: PeerLibrary project update
Date: 2013-10-18 06:06
Category: assignment3
Tags: peerlibrary
Slug: mmilutinovic-assign3
Author: Mitar

[PeerLibrary](http://peerlibrary.org) development has been progressing steadily. The last major feature added is a package named [PeerDB](https://github.com/peerlibrary/meteor-peerdb) which aims to bring support for easy collaborative database around MongoDB. The idea is that a developer does not have to think about all the aspects needed for implementing a database which can support collaborative process, but designs the database so that it works for one user, but then PeerDB layer extends this for use by multiple users editing the same object. For this PeerDB makes sure all references between documents are properly kept in sync and (not yet implemented) that no state of the document is lost, but all versions are stored to be possibly reviewed by community, restored, or just viewed.

Because team is small it is really easy to observe some commit dynamics. For example, overall activity dies very quickly off if only one person is active. But immediately when two persons are working on the project, activity is sustained. It seems they both have a feeling that progress is being made and continue participating. We also take part in hackathons which create bursts of activity which sometimes kill activity afterwards (recuperation period) or sometimes triggers sustained activity after a pause. So it can server both as "wake up" and "sleep" triggers.

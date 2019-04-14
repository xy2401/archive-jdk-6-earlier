
早期jdk备份。


        echo '```' > checksum.md
        echo checksum >> checksum.md
        echo md5sum >> checksum.md
        find ./* -type f -exec md5sum "{}" + >> checksum.md
        echo sha256sum >> checksum.md
        find ./* -type f -exec sha256sum "{}" + >> checksum.md
        echo sha512sum >> checksum.md
        find ./* -type f -exec sha512sum "{}" + >> checksum.md
        echo '```' >> checksum.md


校验和[checksum](checksum.md)
 

# reference

[raphaello.univ-fcomte.fr - /FTP/Java/Jdk/](http://raphaello.univ-fcomte.fr/FTP/Java/Jdk/)




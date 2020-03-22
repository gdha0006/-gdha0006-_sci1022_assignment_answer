# -gdha0006-_sci1022_assignment_answer
 1. curl http://www.gutenberg.org/cache/epub/2265/pg2265.txt > hamlet.txt
  % Total   % Recieved  % Xfred Average Dload Speed Upload   Time Total  Time Spent  Time Left Current Speed
100   180k  100    180k 0     0     82879          0          00:00:02    00:00:02    --:--:--     82916
  mkdir ~/ebooks
  mv hamlet.txt ~/ebooks
  ls ~/ebooks
hamlet.txt
 2.  ls -lh ~/ebooks
total 184K
-rw-rw-r--+ 1 gdha0006 Domain Users 181K Mar 23 01:10 hamlet.txt
 cd /usr/lib
/usr/lib$ pwd
/usr/lib
/usr/lib$ ls
charset.alias  engines-1.1/  groff/          p11-kit-proxy.so@  pkcs11/   security/
csih/          gawk/         libbash.dll.a*  perl5/             sasl2_3/  terminfo@ 
 3. (Need to Reset and open a new window) curl http://www.gutenberg.org/cache/epub/2265/pg2265.txt > hamlet.txt
  % Total   % Recieved  % Xfred Average Dload Speed Upload   Time Total  Time Spent  Time Left Current Speed
  100 180k  100  180k   0     0       66983          0        00:00:02    00:00:02    --:--:--     66983
 wc hamlet.txt
5307 32252 1884406 hamlet.txt
4. head -n 3447 hamlet.txt | tail -1 
Is thought-sicke at the act
5. grep -i hamlet hamlet.txt | wc 
109 702 4278
109 lines

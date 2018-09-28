Linux: VMA use-after-free #LocalRoot

CVE-2018-17182


Fixed in the following upstream stable kernels, released today:
4.18.9
4.14.71
4.9.128
4.4.157

Attaching an ugly exploit for Ubuntu 18.04, kernel linux-image-4.15.0-34-generic at version 4.15.0-34.37.I


test your Server For This Vuln:
gcc -O2 -o vma_test vma_test.c -g && ./vma_test


#Use Exploit:
t takes about an hour to run before popping a root shell. Usage: First compile with ./compile.sh, then run ./puppeteer. Example run:

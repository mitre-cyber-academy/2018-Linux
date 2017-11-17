# Super Secret Backdoor

### Description for competitors

Someone has backdoored my VM! Find the backdoor to get the flag.

### Description for whitecell

The flag is sitting in /flag.txt, but it is owned by root. The only way to read this flag is to notice that sed has the suid bit set. In order to retrieve the flag, all you'll have to do is run `sed '' /flag.txt`

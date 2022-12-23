# bash-ascii-christmas-tree
Christmas Tree in ASCII art 
```
#!/bin/bash

STAR="\e[5;33m*\e[0m\e[1;32m"
O="\e[0m\e[1;31mo\e[0m\e[1;32m"
RED="\e[31m"
GREEN="\e[32m"
ENDCOLOR="\e[0m"

echo -e "
       ${STAR}
      /.\\
     /${O}..\\
     /..${O}\\
    /.${O}..${O}\\
    /...${O}.\\
   /..${O}....\\
   ^^^[_]^^^
${RED}M${GREEN}E${RED}R${GREEN}R${RED}Y ${GREEN}C${RED}H${GREEN}R${RED}I${GREEN}S${RED}T${GREEN}M${RED}A${GREEN}S!${RED}!${GREEN}!${RED}${ENDCOLOR}
"
```

![](https://i.imgur.com/uxNmYRl.gif)

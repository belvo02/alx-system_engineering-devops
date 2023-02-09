(belvo㉿kali)-[~]
└─$ cd alx-system_engineering-devops/
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops]
└─$ git pull                         
Already up to date.
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops]
└─$ la
0x00-shell_basics  .git  README.md
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops]
└─$ mk dir 0x01-shell_permissions
Could not find command-not-found database. Run 'sudo apt update' to populate it.
mk: command not found
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops]
└─$ mkdir 0x01-shell_permissions 

                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops]
└─$ cd 0x01-shell_permissions        

                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ la
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ touch 0-iam_betty
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ vi 0-iam_betty
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ chmod u+x 0-iam_betty  

                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ whoami
belvo
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ touch 1-who_am_i 
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ vi 1-who_am_i 
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ chmod u+x 1-who_am_i 
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ touch 2-groups   
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ vi 2-groups  
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ chmod u+x 2-groups       
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ touch 3-new_owner
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ vi 3-new_owner
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ chmod 3-new_owner  

chmod: missing operand after ‘3-new_owner’
Try 'chmod --help' for more information.
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ chmod u+x 3-new_owner

                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ la
0-iam_betty  1-who_am_i  2-groups  3-new_owner
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ touch 4-empty    
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ vi 4-empty    
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ chmod u+x 4-empty        
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ touch 5-execute
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ vi 5-execute
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ chmod u+x 5-execute           
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ touch 6-multiple_permissions
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ vi 6-multiple_permissions
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ chmod u+x 6-multiple_permissions
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ touch 7-everybody           
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ vi 7-everybody           
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ cat 7-everybody                 
#!/bin/bash
chmod ugo+x hello
                                                                             
┌──(belvo㉿kali)-[~/alx-system_engineering-devops/0x01-shell_permissions]
└─$ chmod u+x 7-everybody           
                                                                             

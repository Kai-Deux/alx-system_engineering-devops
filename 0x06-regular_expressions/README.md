# TASKS
0. ![](../../Downloads/ec65557f0da1fbfbff6659413885e4d4822f5b1d.png)
## REQUIREMENTS
    - The regular expression must match `School`
    - Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method
- Example: 
```sylvain@ubuntu$ ./0-simply_match_school.rb School | cat -e
School$
sylvain@ubuntu$ ./0-simply_match_school.rb "Best School" | cat -e
School$
sylvain@ubuntu$ ./0-simply_match_school.rb "School Best School" | cat -e
SchoolSchool$
sylvain@ubuntu$ ./0-simply_match_school.rb "Grace Hopper" | cat -e
$```
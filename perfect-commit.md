### How to add perfect commit
Golden rule for git commit is <mark>Single Commit for Single task</mark>
Assume senario that you want to add part of the change in a file to your specific commit. just use fllowing command and choose specific change should add or not using (y/n)
`git stage -p <file-name-to-stage-change>` 

###  Add a perfect matching commit message  
To add a perfect maching commit follow this pattern
    1. Subject - concise summery of what happened
    2. Body - more detailed explanation
                - what is now different than before?
                - what the reason for the change ?
                - Is there anything to watch out for/ anything particularly remarkable

can use   
`git commit`  
command to open editor to the add commit or can add commit using following command
`git commit -m "commit message"`  
here -m flag to specify the message
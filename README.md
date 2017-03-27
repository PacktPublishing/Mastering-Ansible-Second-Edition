# Mastering Ansible Second Edition
This is the code repository for [Mastering Ansible Second Edition]( https://www.packtpub.com/networking-and-servers/mastering-ansible-second-edition?utm_source=github&utm_medium=repository&utm_content=9781787125681), published by Packt. It contains all the supporting
project files necessary to work through the book from start to finish.

## About the Book
This book provides you with the knowledge you need to understand how Ansible 2.1 works at a fundamental level and leverage its advanced capabilities. You'll learn how to encrypt Ansible content at rest and decrypt data at runtime. You will master the advanced features and capabilities required to tackle the complex automation challenges of today and beyond.

## Instructions and Navigation
All of the code is organized into folders. The commands and instructions will look like the following:

    --- 
  - hosts: localhost 
    gather_facts: false 
 
  vars: 
 - a_var: derp 
 
  pre_tasks: 
  - name: pretask 
      debug: 
       msg: "a pre task" 
      changed_when: true 
      notify: say hi 
 
  roles: 
   - role: simple 
      derp: newval 
 
  tasks: 
    - name: task 
      debug: 
        msg: "a task" 
      changed_when: true 
      notify: say hi 
 
  post_tasks: 
    - name: posttask 
      debug: 
        msg: "a post task" 
      changed_when: true 
      notify: say hi

## Related products:
* [Learning Ansible 2 - Second Edition](https://www.packtpub.com/networking-and-servers/learning-ansible-2-second-edition?utm_source=github&utm_medium=repository&utm_content=9781786464231)

* [Ansible 2 for Beginners [Video]](https://www.packtpub.com/networking-and-servers/ansible-2-beginners-video?utm_source=github&utm_medium=repository&utm_content=9781786465719)

* [Implementing DevOps with Ansible 2](https://www.packtpub.com/networking-and-servers/implementing-devops-ansible-2?utm_source=github&utm_medium=repository&utm_content=9781787120532)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.

# 0x02. Session Authentication

### Background Context

In this project, you will implement Session Authentication without installing any additional modules. In industry practice, it's recommended not to create your own session authentication system but to use existing modules or frameworks, such as [Flask-HTTPAuth](https://intranet.alxswe.com/rltoken/_ZTQTaMKjx1S_xATshexkA) in Python-Flask. However, for learning purposes, we will walk through each step of this mechanism to understand it.

### Resources

Read or watch:
- [REST API Authentication Mechanisms](https://intranet.alxswe.com/rltoken/oofk0VhuS0ZFZTNTVrQeaQ)
- [HTTP Cookie](https://intranet.alxswe.com/rltoken/peLV8xuJ4PDJMOVFqk-d2g)
- [Flask](https://intranet.alxswe.com/rltoken/AI1tFR5XriGfR8Tz7YTYQA)
- [Flask Cookie](https://intranet.alxswe.com/rltoken/QYfI5oW6OHUmHDzwKV1Qsw)

### Learning Objectives

By the end of this project, you should be able to [explain to anyone](https://intranet.alxswe.com/rltoken/uWXp4VcY3Dd9UzTtc9N5_A) without using Google:

#### General

- What authentication means
- What session authentication means
- What Cookies are
- How to send Cookies
- How to parse Cookies

### Requirements

#### Python Scripts

- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/env python3`
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the pycodestyle style (version 2.5)
- All your files must be executable
- The length of your files will be tested using wc
- All your modules should have documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
- All your classes should have documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
- All your functions (inside and outside a class) should have documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
- A documentation is not a simple word; it's a real sentence explaining the purpose of the module, class, or method (the length of it will be verified)
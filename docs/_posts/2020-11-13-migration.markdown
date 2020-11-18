---
layout: post
title:  "Migrating from LTI 1.1 (Not moodle specific)"
date:   2020-11-13 20:11:52 -0500
categories: general
---

Moodle let's you do Migration in Place. That is: you toggle your tool from 1.1 to 1.3, fill in the required LTI 1.3 parameters and that's it! All the data is still around. 

**But where did they go?** In the id_token as openid or lti claims.

**How to pass grade back?** You now post score to the lineitem URL passed in the LTI message.

**What about my consumer key?** Well, you will have to prompt the user to do a rebinding of the Moodle issued client_id to the old consumer key.

All of this is covered in a Youtube presentation (LMS agnostic):

<iframe width="560" height="315" src="https://www.youtube.com/embed/aPS_MjGJDXA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---
layout: post
title: "ON-CHAIN DISTRIBUTED COMPUTING"
date: 2017-12-12
---

 Distributed computing seems like an ideal use-case for cryptocoin systems. You can substitute pointless math problems with beneficial computation. This is the line of thinking that drove me to spend the last few days working on my own system and associated coin. However, in doing so, distributed computing seems more and more like a solution that causes more problems than it solves.
 
The existence of projects like BOINC makes the problems of distributed computing seem solved. Large-scale computation is achieved using the spare CPU and GPU cycles of volunteers around the world. Meaningful scientific research has been made possible by this framework. Thus, it would seem that BOINC provides an excellent framework to replicate in a commercial venture.

The issue with this line of thinking is that it is flat out untrue. The framework employed by BOINC is wrought with redundant computation, a poor rewarding system, and is subject to abuse by motivated parties.

Verifiable computation is still an unsolved problem in data science. There is no simple way to verify that a solution is correct without doing all the work to get to that solution yourself. BOINC projects solve this with Verification by Replication. Each computation performed by one user is then repeated by at least one other. If the solutions match, the computations are considered to be correct.
Now, this is obviously a slow process, and it is impossible to immediately reward the user for their contribution. This strategy also essentially wastes the CPU time of someone performing the verification work.

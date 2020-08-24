---
title: "Software Engineer"
collection: career
type: "Software R&D, Application Development"
permalink: /career/2020-engineer-samsung
venue: "Samsung R&D Institute Bangladesh (SRBD)"
date: 2020-01-15
location: "Dhaka, Bangladesh"
---

I have worked on multiple system modules. My main contribution was in developing
Samsung Cloud Service (system API) on Tizen 5.5 OS for Galaxy Watch3 models and later
development in Android platform.

Apart from module specific function implementations, there were several key challanges
that required thoughtful programming.
<ul>
  <li>**Resource stringency-** Watches have low ram and lower battery capacity but constant usage.
  Ever running background (Daemon) services, like Autobackup feature of SCloud and system (non-blocking) service,
  such as Backup/Restore of SCloud, needed to be heavily optimised and cautiously coded to avoid any potential performance pitfalls </li>
  <li>**Parallelism & Concurrency-** System services such as SCloud needs to be non-blocking, that is to provide services to other system or user
  applications as they come without blocking main thread. This specification along with runtime optimization, required concurrent & multithreaded
  design across all layers of the Scloud service. </li>
  <li>**Compatibility-** SCloud service needed to be cross device, cross platform compatible. So that,
  a backup of device A in OS version 2.0 can be restored in device B OS version 1.0. This challenge can lead to some complicated scenarios, which in turn
  create security breach, memory leaks and many other problems if not properly handled. </li>
</ul>

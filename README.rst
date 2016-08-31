
a political manifesto about distributed systems
===============================================


Motivation
----------

Even before the industrial revolution new leaps in technology have
slowly trickled into society such that the existing power structures
are reinforced instead of challenged. Here we examine why distributed
software systems that exist today also reinforce these older existing
power structures instead of dispersing the authority among many more
actors in the system. We discuss how future protocols and distributed
systems may be designed to challenge existing power structures with
anarchist software design principles that not only protect our human
rights but also make systems much more robust in the face of partial
system outages.


Scope
-----

We have several objectives:

* identify software design principles which support human rights
  (privacy and article 19 right to free assembly), robust security and
  correctness.

* examine how existing distributed systems do not adequately express
  our desired design principles

* Software development needs sustainable economic models: An analysis
  of existing economic models supporting the development of Internet
  protocols and distributed systems; showing how our current economic
  structures do not effectively support the development of much needed
  infrastructure we all rely on.


Glossary
''''''''

ambient authority: an actor is said to have ambient authority if it
has the same authority as many other actors in the system

excess authority: an actor is said to have excess authority if it
posseses more authority than is necessary to perform it's task

least authority: an actor is said to have least authority if it only
posseses the minimum amount of authority to perform it's task. For a
thorough introduction to this software design principle please read
`The Structure of Authority`_

.. _`The Structure of Authority`: http://www.erights.org/talks/no-sep/secnotsep.pdf



Call for the abolishment of systems administrators
''''''''''''''''''''''''''''''''''''''''''''''''''

An "administrator" actor in a software system has more authority than the
other actors. This violates the principle of least authority and
creates a deep pocket of excess authority. State actors such as the
NSA take advantage of these systemic flaws by targetting sys admin
(see "I hunt sysadmin" below). Once the attacker compromises the
admin's laptop they will then be able to access all of the
infrastructure that the sys admin was able to access. We should
therefore strive to create software systems without an "admin" role.



anarchism == principle of least authority
'''''''''''''''''''''''''''''''''''''''''

Noam Chomsky defines anarchism as: the extension of the idea that all
authority must be justified.

The principle of least authority is a software design principle that
is defined as: every module must be able to access only the
information and resources that are necessary for its legitimate
purpose.

That is, all software modules must only have authority they are
justified to have. This is anarchism applied to software design!



Evaluation of existing distributed system designs
-------------------------------------------------

Exemplary usage of anarchist design principles
----------------------------------------------

Human rights considerations for distributed ciphertext storage systems
----------------------------------------------------------------------

Problematic economic models for supporting software development
---------------------------------------------------------------



Bibliography
''''''''''''

#. wikipedia article about ambient authority
   https://en.wikipedia.org/wiki/Ambient_authority

#. The Structure of Authority: Why security is not a separable concern
   http://www.erights.org/talks/no-sep/

#. Robust Composition: Towards a Unified Approach to Access Control
   and Concurrency Control
   http://www.erights.org/talks/thesis/

#. IRTF HRPC's draft-doria-hrpc-report-01
   https://www.ietf.org/id/draft-doria-hrpc-report-01.txt

#. IRTF HRPC's draft-tenoever-hrpc-research-05
   https://www.ietf.org/id/draft-tenoever-hrpc-research-05.txt

#. leaked NSA document: I Hunt Sys Admins
   https://search.edwardsnowden.com/docs/IHuntSysAdmins2014-03-20nsadocs

#. User Interaction Design for Secure Systems by Ka-Ping Yee
   http://www.eecs.berkeley.edu/Pubs/TechRpts/2002/CSD-02-1184.pdf

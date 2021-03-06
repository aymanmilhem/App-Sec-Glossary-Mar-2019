## My Study Notes
#### Notes I take for my study will be added here
##### This is mainly for practicing and familiarizing myself with git 
Bash and git hub

from: 
https://www.techopedia.com/2/27825/security/the-basic-principles-of-it-security

## **IT Security Best Practices/ Security Principles**  
1. **Balance Protection with Utility**  
2. **Split Up the Users and Resources**  
3. **Assign Minimum Privileges**  
4. **Use Independent Defenses**  
5. **Plan for Failure**  
6. **Record, Record, Record**  
7. **Run Frequent Tests**  

> ### **The Takeaway**
>
>IT security is a challenging job that requires attention to detail at 
the same time as it demands a higher-level awareness. However, like many 
tasks that seem complex at first glance, IT security can be broken down 
in to basic steps that can simplify the process. That’s not to say it 
makes things easy, but it does keep IT professionals on their toes.

Also, an image i keep seeing on the iQualify pages is: 

![The Security 
Pyramid](https://iqfy-storage.imgix.net/sFmmI3LTRCVrXMjHWoyN_security_pyramid___principles.jpg)

 

> ## Important
>In the **Written Assessment**, you will be asked to explain three 
principles 
of your choice (except Defense in Depth) and then analyse one of those in 
more detail. 


> **Bingo**!!
********************************************************************
## Notes from 2019-03-07
* Security by design:
  * Embed security at every level of the SDLC, from 
requirements to testing to deployment.
  * "shift left" in sw dev parlance (as in _"shift security to 
the left of the timeline_", i.e. **towards the earlier steps 
of the SDLC**.)

## Common Security Principles: 
> "... have been organised along the SDLC task they apply to 
>the most."  
### System Design and Architecture
#### Defense in Depth  
> Defense in Depth – Multiple layers of control make it harder 
to exploit a system.  
#### Keep It Simple 
**Keep it simple / Economy of Mechanisms** - Keep things 
simple.  

#### Minimize attack surface  
* Use a positive security model/ minimize _Attack Surface_- 
Reduce _entry points_ that can be exploited by malicious 
users.  

* Videos: 
  * Map exposure points and data passageways.
  * Security Through Obscurity.

* A related principle:  
  * Use Positive security model/ Whitelisting.  
    * Whitelisting: access is denied by default and only whitelisted 
entities are allowed access.  

## Access:
These principles relate to access rights given to users of the 
application: 
* ### Least Privilege:  
  * just having enough access level to do the job.
* ### Separation of duties:  
  * Different entities lave different roles.

* ## Complete Mediation:  
  * Access to all resources of a system are always validated.

## Implementation  
* These principles might be especially useful to guide you 
during implementation:  
 * Fail Securely: 
   * Limit amount of information exposed on errors encountered by a 
system.

## Psychological Acceptability
**Security implemetation should protect a system but not hamper users of 
the system.**  

## Operations
This is about how to respond to incidents. Often enough, first the 
incident is not identified immediately, second _the issue is not 
resolved appropriaely either_.  

### Fix Secutiry issues correctly 
...

### An Example is given:  
**Defense in depth**
*****************************************************

# Security Standards and Regulations
## Overview:  
* The NZ Information Security Manual (NZISM)  
* The NZ Privacy act  
* The European General Data Protection Regulation 
(GDPR)

## 1. Defenitions
**In this unit you'll learn** about **legal 
requirements and standards** that concern 
application security.

### Compliance

### Standard

### Regulation

## 2. Security Standards:  
> "The main security standard that applies to 
>application security in New Zealand is the 
>NZISM"

## Instructions for activity
Identify at least 5 items that you think a web 
app should/ must comply with.
Express each of them in the form of an 
instruction  (READ-DO) to a web app development 
team.

### Items Identified: 
* Application whitelisting: Only approved 
applications are used on agency controlled 
systems.
* System user permissions.
* System administrator permissions.

# 2018-03-11-Home
## Application Security Mechanisms  
![Application Security Pyramid - 
Mechanisms](https://iqfy-storage.imgix.net/uZswdXDCS4OYc4yyCEdS_security_pyramid___mechanisms.jpg)  

## Core Security Mechanisms  
![Security Mechanisms](https://iqfy-storage.imgix.net/41887vvQ9uYaLjkRQRAg_mechanisms_and_aims.png)

### Authentication:  
_is the act of confirming that someone is who 
they claim to be_. **Secure Authentication 
Mecanisms include**:  
* Enforcing Strong passwords.
* Logging failed logins and pw changes.
* locking users out after failed login.
* implementing two-factor authentication.
* Taking care with forgotten pw function.
* Using POST method.

### Authorizatin:  
*is the act of verifying that a __previously authenticated__ user is allowed to perform a given operation or act on a given resource*.
**OFTEN KNOWN AS ACCESS CONTROL**
__Secure authorization mechanisms include__:  
* Checking authorization to access every function/ page.
* Checking access to data/ context.
* Always checking access on the server not the client.

### Data Validation:  
(*is considered my many to be the most important mechanism in secure coding*),  
*And is: checking that the date received from a client corresponds to what the application expects in terms of __length, format, data type, etc.__ It includes both whitelisting and blacklisting. Secure validation is always done on the server, as the client may be compromised*.

### Session Management:  
_is a method to keep track of the user's state in 
a multi-step workflow, **including keeping data 
collected at one stage for use at another 
stage.**_  
**Managing sessions securely includes:**
* limiting the session's lifespan.
* Generating new IDs each login.
* Using existing robust session management 
solutions _rather than building your own_.

### Error Handling:  
**is the practice of always expecting the 
unexpected (expeting errors to happen), and 
always processing the error securely, which 
includes logging it and stopping the current 
task**  

### Logging:  
**Keeps track of important events that happen 
in the application** _such as login successes 
and failures, use of admin functions, password 
resets and changes, and some applicatin 
errors_.

### Encryption:  
**Transforms data in order to make it difficult 
for and outsider to interpret**.


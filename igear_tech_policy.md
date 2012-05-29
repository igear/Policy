#iGear Tech Policy
This document reflects current policy and is subject to change

The current VPS will be refferred to as **iGearVPS**

##New Projects
###Project name
All projects will recieve a concise, distinct, typable and memorable project name that consists of a single word.

> N.B. The project name is never the the client name!

This project name will be used in folder structure naming, Git repo nameing, config files, password storage, database naming, buildscripts, and everyday communication.

###Location on the server
Unless a project belongs to a client with their own user-account on the server (see *Server Users* below) projects are stored as folllows:

	/home/igearint/projects/projectname

And made available publicly as

	http://projectname.igearinternet.nl


###Github
Whenever applicable a project will be versioned in Git and origined to GitHub. The git repo has the project name.
(There's currently no policy on CamelCasing.)



##New Domains and DNS
Domains will be registered via **Openprovider.nl** (registrar) and **CloudFlare** is the SOA nameserver.



##Wireframes

Wireframes are stored under

	/home/igearint/wireframes/projectname

And made availabe as

	http://wireframe.igearinternet.nl/projectname


##Facebook Apps
Facebook apps are considered to be projects that is **delivered through an iFrame** and **requires https**.

They are stored under

	/home/igearint/apps/projectname

And made availabe as

	http://apps.igearinternet.nl/projectname

##Server Users
A client gets his own account on the server as soon as there are one or more full domains referencing to projects on iGearVPS.

In any other case the project structure is as described under *Location on the server*
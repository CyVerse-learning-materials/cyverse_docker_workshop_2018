|CyVerse logo|

CyVerse Docker Workshop
------------------------

**Workshop Code of Conduct**
============================

All attendees, speakers, sponsors and volunteers at our workshop are required 
to agree with the following code of conduct. Organisers will enforce this code 
throughout the event. We are expecting cooperation from all participants to 
help ensuring a safe environment for everybody. 

This Code of Conduct taken from 
http://confcodeofconduct.com/. See http://www.ashedryden.com/blog/codes-of-conduct-101-faq
for more information on codes of conduct.

**Learning objectives**
=======================

Participants will learn key containerization concepts for developing 
reproducible analysis pipelines, with emphasis on container lifecycle 
management from design, execution and scaling. The workshop will cover key 
concepts containers such as defining the architecture of Containers, building 
Docker images and pushing them to public and private repositories. 

**Who Should Attend**
=====================

Faculty, Postdocs, graduate students who use and analyze data of all
types (genomics, image data, from animals, plants, etc.).

**Workshop Level**
==================

This workshop focused on beginning users with little to no previous container
experience.

Intermeidate and advanced users attend to better understand container capabilities 
and resources, including deploying their own tools and extending these analyses 
into Cloud and HPC.

**Need Help?**
==============

You can reach the lead instructor, Upendra Devisetty, at upendra@cyverse.org. 
You can also talk to any of the instructors or TAs if you need immediate help, 
or (in an emergency) call 911.


**Pre-Workshop Setup**
======================

These are the minimum Setup Instructions for the CyVerse Docker workshop, University of Arizona, on March 1st 2018.

.. list-table::
    :header-rows: 1

    * - Prerequisite
      - Notes
      - Links
    * - Wi-Fi-enabled laptop
      - You should be able to use any laptop using Windows/MacOS/Linux.
        We **strongly recommend** Firefox or Chrome browser; **We do not recommend**
        **Microsoft Edge Browser**. It is recommended that you have administrative/install 
        permissions on your laptop.
      - - `Download FireFox <https://www.mozilla.org/en-US/firefox/new/?scene=2>`_
        - `Download Chrome <https://www.google.com/chrome/browser/>`_
    * - Github Account
      - Please ensure that you have a Github account if you don't have one already
      - Register for your Github account at `https://github.com/ <https://github.com/>`_.
    * - Dockerhub Account
      - Please ensure that you have a Dockerhub account if you don't have one already
      - Register for your Dockerhub account at `https://dockerhub.com/ <https://dockerhub.com/>`_.
     * - Text Editor
      - Please ensure that you have a Text editor of your choice. Any decent text editor would be sufficient and
        recommended ones include Sublime2 and Atom
      - - Register for Sublime at `https://www.sublimetext.com/ <https://www.sublimetext.com/>`_.
        - Register for Atom at `https://atom.io/ <https://atom.io/>`_.
 
**Optional Download Extras**

These are some extra downloads that aren't required for the workshop, but which
provide some options for functionalities we will cover.

.. list-table::
    :header-rows: 1

    * - Tool
      - Notes
      - Link
    * - SSH Clients (Windows)
      - PuTTY allows SSH connection to a remote machine, and is designed for
        Windows users who do not have a Mac/Linux terminal. MobaXterm is a single 
        Windows application that provides a ton of functions for programmers, webmasters, 
        IT administrators, and anybody is looking to manage system remotely
      - - `Download PuTTY <https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html>`_
        - `Download mobaXterm <https://mobaxterm.mobatek.net>`_

Workshop Topics
===============
These are the topics for the CyVerse Docker workshop, University of Arizona, on March 1st 2018.

- Installing Docker on laptop (Mac/Windows/Linux) and on cloud
- Running Docker containers from prebuilt image
- Building Docker images using Dockerfile
- Building webapps using Docker
- Docker registries (Docker cloud, Docker hub, quay.io and local registries)
- Automated Docker image building from github and bitbucket
- Exposing ports on running Containers
- Working with volumes (creating and binding volumes)
- Managing data for analysis in Docker containers
- Improving your data science workflow using Docker containers
- Putting it all together: Deploying an app in Discovery Environment
- Portainer demo for managing Docker containers and images (https://portainer.io/) 
- Play-with-Docker demo for testing Docker containers (http://www.play-with-docker.com/) 

**About CyVerse**
=================

**CyVerse Vision:** Transforming science through data-driven discovery.

**CyVerse Mission:** Design, deploy, and expand a national
cyberinfrastructure for life sciences research and train scientists in
its use. CyVerse provides life scientists with powerful computational
infrastructure to handle huge datasets and complex analyses, thus
enabling data-driven discovery. Our powerful extensible platforms
provide data storage, bioinformatics tools, image analyses, cloud
services, APIs, and more.

While originally created with the name iPlant Collaborative to serve
U.S. plant science communities, CyVerse cyberinfrastructure is germane
to all life sciences disciplines and works equally well on data from
plants, animals, or microbes. By democratizing access to supercomputing
capabilities, we provide a crucial resource to enable scientists to find
solutions for the future. CyVerse is of, by, and for the community, and community-driven needs
shape our mission. We rely on your feedback to provide the
infrastructure you need most to advance your science, development, and
educational agenda.

**CyVerse Homepage:** `http://www.cyverse.org <http://www.cyverse.org>`_

**Funding and Citations**
=========================

CyVerse is funded entirely by the National Science Foundation under
Award Numbers DBI-0735191 and DBI-1265383.

Please cite CyVerse appropriately when you make use of our resources,
`CyVerse citation
policy <http://www.cyverse.org/acknowledge-cite-cyverse>`__

.. |CyVerse logo| image:: ./img/cyverse_rgb.png
  :width: 500
  :height: 100
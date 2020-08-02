# Introduction to DevOps

- 1 What is DevOps?

DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to 
deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations
using traditional software development and infrastructure management processes. This speed enables organizations to 
better serve their customers and compete more effectively in the market.

DevOps consists of new product features, bug fixes, security updates and code refactoring

- 2 Why DevOps?

DevOps consists of bridging the gap between development and operations. It has stopped the monolith architecture,
enable efficient process. 


- 3 Challenges of DevOps

Breaking down teams from individual silos and bridge the gap of development and operations 

Awareness is crucial since scaling DevOps across the whole organisation may not be beneficial. Different apartments have
different needs. 

- 4 Benefits of DevOps

    - Faster time market - adapt to changing markets better, and grow more efficient at driving business results. The 
    DevOps model enables developers and operations teams to achieve these results. For example, microservices and 
    continuous delivery let teams take ownership of services and then release updates to them quicker.   
    - Improved team collaboration - Build more effective teams under a DevOps cultural model, which emphasizes values 
    such as ownership and accountability. Developers and operations teams collaborate closely, share many 
    responsibilities, and combine their workflows. This reduces inefficiencies and saves time (e.g. reduced handover 
    periods between developers and operations, writing code that takes into account the environment in which it is run).     
    - Continues release cycles - Increase the frequency and pace of releases so you can innovate and improve your
     product faster. The quicker you can release new features and fix bugs, the faster you can respond to your 
     customers’ needs and build competitive advantage. Continuous integration and continuous delivery are practices 
      automate the software release process, from build to deploy.   
    - Automated scaleable environments - Operate and manage infrastructure and development processes at scale. 
    Automation and consistency help you manage complex or changing systems efficiently and with reduced risk. 
    For example, infrastructure as code helps manage development, testing, and production environments in a 
    repeatable and more efficient manner.   
    - Increase quality due to automated testing - Ensure the quality of application updates and infrastructure changes
     to reliably deliver at a more rapid pace while maintaining a positive experience for end users. Use 
     practices like continuous integration and continuous delivery to test that each change is functional and safe. 
     Monitoring and logging practices help you stay informed of performance in real-time.
   
  test   
# DevOps

##CAMS Model
- Sharing 
- Measurement 
- Automation 
- Culture 

## Four pillars of DevOps
- Ease of use: everyone on the team will use this, which is why documentation is important.
- Flexibility: things change at incredible rate, you don't want to change that fast but adapt accordingly.
- Robustness: we need 100% uptime, fast and robust deployment
- Cost: cost of downtime, cost of slow innovation, cost of time to market, cost of infrastructure

## Bare Metal Mainframes
- your computer = your problem
- from planning, to serving, maintaining, securing, resourcing, setting up - everything except producing 

## IaaS
Infrastructure As A Service

- rent out the computing and storage power you need
- shared responsibility model: service provider has the responsibility of securing and maintaining the cloud - you have to do the security in the cloud. 
- rent out by the second, increase as you grow, consume only what you need
- technical knowledge of how to build systems needed
- only mental renter per second 
- i.e. AWS, Alibaba Cloud, Microsoft Azure

## PaaS
Platform As A Service

- built on top of IaaS
- you still need some technical know-how
- has a better graphical interface
- relatively more expensive per second
- depends on the cost of maintenance
- less control more vendor lock-in
- i.e. Heroku


## SaaS
Software As A Service

- highest level of abstraction
- the pure version means: no donwloads, no CDs or physical install
- all happens in the cloud
- access via browser or API
- if we need to download this means we will need to update and expose our sw to a different environment

The way we develop has changed, it is no longer as hierarchical with Agile and the ability of having software integrated which means that the sprint is shorter, it can be pushed/go live quicker, and the feedback loops are stronger.

## Environments
An environments is a location where code runs and data lives.

Github is not an environment really, maybe Github pages.

Your machine is an environment because code runs and you develop software and web apps and other apps.

What environments are there?
- Developments:
    - where you write your code, Py, Sql, Html - i.e. computer
- Testing:
  - external, has its own tools and infrastructure that runs the code
- Production:

Code pipelines: move between the environments.
Testing: ensures functionality and quality of the website.
Objective: increase speed of learning and developing -> increase feedback loops -> increase innovation.

"It's working on my computer" - this is the main issue in DevOps, to avoid this you must standardise the environment.


## pbm in development - standardise virtual environment
Develop a culture of DevOps: giving them ownership of their pipelines and that everyone in the organisation understands why we are doing things.

Tests - make sure that whatever you are creating is itself a standardised environment.

## pbm in operations - don't always receive code, power, electricity - has its own operational issues, you have to buy them and maintain them


## Node
- can mean an instance, a machine but in this case it means JS

## ```Typical Vagrant Questions```
1. What is Vagrant? 
Vagrant is an open-source software productfor building and maintaining portable 
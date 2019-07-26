<p align="center">
  <img src="_images-angularcli/1-angular-cli-logo-1.png" alt="angular cli logo" title="angular cli" width="200" />
</p>

Angular CLI
=====================

Welcome
---------------------

About the Course/Tutorial
---------------------
Hi All, I'm **`Dinanath Jayaswal, Senior UI/Web Developer and Adobe Certified Expert Professional`**, I wanna welcome you to `Angular CLI step by step guide from basics to advanced`. This `Angular CLI Tutorial` will help you to understand: 
- How to work with Angular CLI (Angular Command Line Interface)
- How to create Angular Projects/Application scaffold/structure in a short time
- Show a demo on how to create an Angular application, Components, Services, Directives, Routing and Navigation, Pipes, Modules, etc. using Angular CLI
- Helps to learn how to use and master Command Line Interface offered by Angular
- Helps in creating and serving Angular projects on the fly
- How to work and use with different commands of Angular CLI

Who is this for? 
---------------------
This Course/Tutorial is ideal for:
- Freshers and aspiring UI (JavaScript/Angular) developers
- UI Developers/Designers
- Developers upgrading from AngularJS 1.x to Angular 2 or above
- Full Stack Developers
- Technical/Team Leads
- Architects, Technical Project Managers, QAs

This course/Tutorial is for anyone and everyone, Almost everyone! Fresher/Newcomer as well as experienced UI/frontend/Web Developers who are interested in boost skills and further career in Angular world - by learning new latest dynamic tools/utilities which helps to scaffold Angular application to become a hi-tech developer.

Why learn Angular and Angular CLI?
---------------------
**Angular** - Angular is one of the most widely used JavaScript framework used to create scalable, enterprise, and performant client-side web applications. It provides an ecosystem for the development of client-side web applications. The ecosystem for development may include external tools or libraries as well. The ecosystem process includes project bootstrapping, development operations/tools, testing, and build support. One of the best features of Angular framework is that it is quite flexible when it comes to the usage of external libraries apart from the scalability it provides. With Angular framework adoption being high, performance management of the application is community-driven indirectly driving better job opportunities.

**Angular CLI** - Creating Angular application boilerplate manually is tedious, time-consuming monotonous and laborious. `Angular CLI helps to create required Angular application/project scaffolding chunks accurately with Google standards and in no time with ease`.

Course/Tutorial achievement
---------------------

Course/Tutorial Goal
---------------------
After completing/attending this Course/Tutorial, participants should be able to: 
1. Create and work on a real-time Angular Project with Angular CLI (Angular Project setup with Angular CLI)
2. Create and use many-core building blocks of Angular application like Components, Services, Directives, Routing and Navigation, Pipes, Modules, etc.

Topics included/covered
===================== 
1. [Angular CLI Introduction](#01-angular-cli-introduction)
    - 1.1. [What is Angular CLI](#11-what-is-angular-cli)
    - 1.2. [Why use Angular CLI](#12-why-use-angular-cli)
    - 1.3. [Benefits Advantages of Angular CLI](#13-benefits-advantages-of-angular-cli)
2. [Getting Started with Angular CLI](#02-Getting-Started-with-Angular-CLI)
    - 2.1. [Pre-requisites](#21-pre-requisites)
    - 2.2. [Tools required to install Angular CLI](#22-tools-required-to-install-angular-cli)
    - 2.3. [Steps to Setup the Angular CLI development environment](#23-steps-to-setup-the-angular-cli-development-environment)

01 Angular CLI Introduction
=====================

1.1. What is Angular CLI
--------------------- 
- `Angular CLI = Angular Command Line Interface`, its Command Line utility for Angular (website:  https://cli.angular.io/)
  - Angular CLI is Command Line Interface/Tool for creating, serving and managing Angular projects
  - The quickest and easiest way of creating/starting an Angular app is through the `Angular CLI (Command Line Interface)`
  - It allows/helps the developer to build/generate building blocks of Angular application like `Components, Services, Directives, Routing and Navigation, Pipes, Modules`, etc. with best practices, quicker and easier

**Angular CLI is Angular command line tool helps to:**
- Create Angular applications faster and with great consistency
- Create the boilerplate code for angular features like Components, Services, Directives, Routing and Navigation, Pipes, Modules`, etc.
- Creates boilerplate code TypeScript features like Classes, Interfaces, enums
- Angular CLI follows angulars best practices and conventions out of the box
- Run Unit and End-to-End(e2e) tests
- Creates optimized builds for deployment to production

1.2. Why use Angular CLI
--------------------- 
Creating Angular application boilerplate manually is tedious, time-consuming, monotonous and laborious task - it trends to many mistakes. CLI helps to create required angular chunk accurately in no time on the fly. No doubt Angular CLI, will greatly help us improve our productivity with best Angular practices.

Angular CLI eases and makes Angular app/project development process faster. 

| **without Angular CLI**                   | **with Angular CLI**                      |
| ------------------------------------------|-------------------------------------------|
| **We have to do the setup manually**: <br/> 1. download zip/executable/library files,  <br/> 2. extract <br/> 3. follow specific installation process add and  <br/> 4. edit framework/library configuration files etc. according to the project and  | Just install/setup Angular CLI globally on the machine, generate/create new project by using Angular CLI commands and get started with app in no time  |
 
1.3. Benefits Advantages of Angular CLI
---------------------

1.3. What Angular CLI does?
---------------------
- Setup up the Angular Development environment
- Provides required configuration files (angular.json or angular-cli.json) for Angular project/program
- Reduces development efforts tremendously (eliminates manual entries in configuration/index or startup files)

02 Getting Started with Angular CLI
=====================

2.1. Pre-requisites
---------------------
- Node 6.9.0 or higher (website: https://nodejs.org/en) 
- NPM 3 or higher (Node Package Manager - comes inbuilt with Node)
- Basic familiarity with Angular must (Angular 2 and above)

2.2. Tools required to install Angular CLI
---------------------
In this section, we will list/understand the different tools/Softwares/utilities required to set up a local development environment of Angular CLI.

- `Node`, (website: https://nodejs.org/en) 
- `NPM`, (Node Package Manager - comes inbuilt with Node)
- `Angular CLI = Command Line Interface`, Angular CLI (Command Line Interface) for angular (website:  https://cli.angular.io/), 
    - it allows the developer to build/generate building blocks of angular application like component, services, routings, modules, etc. with best practices quicker and easier)
- `Text Editor`
    - Visual Studio Code / Visual Studio Code Insiders (website: https://code.visualstudio.com)
    - Sublime Text, 
    - Atom, 
    - Brackets etc.

2.3. Steps to Setup the Angular CLI development environment
---------------------
In this section, we will learn how to set up a local development environment of Angular CLI to start developing Angular apps with Angular CLI.

1. Download and Install latest node (node comes with npm) (website: https://nodejs.org/en)
<p>
  <figure>
    &nbsp;&nbsp;&nbsp; <img src="./_images-angularcli/2.3.1-nodejs.png" alt="nodejs website" title="nodejs website" width="600" border="2" />
    <figcaption>&nbsp;&nbsp;&nbsp; Image - Nodejs website - https://nodejs.org/en</figcaption>
  </figure>
</p>

2. After installation check installed version of node and npm or verify installation by using command: `node -v` / `node --version` OR `npm -v` / `npm --version`
3. Install Angular CLI (website https://cli.angular.io/) by using command: `npm install -g @angular/cli` (it will install Angular CLI globally (-g))

<p>
  <figure>
    &nbsp;&nbsp;&nbsp; <img src="./_images-angularcli/2.3.2-angular_cli.png" alt="Angular CLI website" title="Angular CLI website" width="600" border="2" />
    <figcaption>&nbsp;&nbsp;&nbsp; Image - Angular CLI website - https://cli.angular.io/</figcaption>
  </figure>
</p>

4. After installation check version of angular CLI or verify installation by using command by using the command: `ng -v` OR `ng --version` (the command returns versions of Angular CLI, node/npm as well as operating system installed on your local machine), you can also verify angular CLI installation by command: `ng` OR `ng --help`

# Campus Course & Records Manager (CCRM)

## Java Dvelopment Kit 24 

## Project Overview

Domain classes (edu.ccrm.domain)

Model the real-world objects such as Course, Student, Instructor, Semester, Enrollment, and associated information (grades, person).

Each class probably has properties (fields) and getter/setter methods.

Service classes (edu.ccrm.service)

Implement business logic for course handling (CourseService) and student handling (StudentService).

These services operate on the domain objects.

Main.java

The program's entry point.

Probably instantiates objects, invokes services, and executes a basic workflow (e.g., registering a student, grading, etc.).

## Evolution of Java
1991 – Oak: Project started at Sun Microsystems for embedded devices, later renamed Java.

1995 – Java 1.0: "Write Once, Run Anywhere" – platform-independent language launched.

1998 – Java 2 (J2SE 1.2): Introduced Swing, Collections Framework, and JVM improvements.

2004 – Java 5 (J2SE 5.0): Major upgrade – Generics, Annotations, Autoboxing, Enums, for-each loop.

2006 – Java 6: Performance improvements, scripting support, JDBC 4.0.

2009 – Oracle acquires Sun Microsystems, takes over Java.

2011 – Java 7: Introduced try-with-resources, Diamond operator (<>), Fork/Join framework.

2014 – Java 8 (huge milestone): Lambdas, Streams API, Optional, new Date-Time API.

2017 – Java 9: Module System (Project Jigsaw), JShell (REPL).

2018 – Java 10/11: Local variable var, HttpClient API; Java 11 became LTS.

2021 – Java 17 (LTS): Sealed classes, Pattern Matching, modernized language.

2023 – Java 21 (LTS): Virtual Threads (Project Loom), String Templates, Record Patterns.

## Java SE vs ME vs EE
**🔹Java ME (Micro Edition)**

Designed for small devices → mobiles, IoT, embedded systems.

Lightweight libraries, subset of Java SE.

Optimized for low memory & CPU.

Example: Old Nokia apps, IoT sensors.

Mostly replaced by Android SDK / Embedded Java.

**🔹Java SE (Standard Edition)**

Core Java platform, foundation of everything.

Runs on PCs, laptops, small servers.

Includes Collections, IO, Networking, Concurrency, Swing/JavaFX.

Used for desktop apps, utilities, small server apps.

Every Java developer starts here.

**🔹Java EE (Enterprise Edition)**

Extension of Java SE for large-scale enterprise apps.

Runs on application servers (Tomcat, GlassFish, JBoss, etc.).

Provides Servlets, JSP, EJB, JPA, JMS, Web Services.

Used in banking, e-commerce, enterprise portals.

Now renamed Jakarta EE under Eclipse Foundation.

## JVM/JRE/JDK Explanation

**🔹 JVM (Java Virtual Machine)**

It is the engine that runs Java programs.

Converts bytecode (.class) → machine code for the OS/CPU.

Provides features: memory management, garbage collection, security.

Platform-dependent (different JVMs for Windows, Linux, Mac).

Think of it as the interpreter of Java.

**🔹 JRE (Java Runtime Environment)**

Provides everything needed to run Java applications.

Includes: JVM + core libraries + supporting files.

Does NOT contain development tools (compiler, debugger).

Used by end-users who only want to run Java apps, not develop.

**🔹 JDK (Java Development Kit)**

Full package for developing and running Java applications.

Includes: JRE + development tools (compiler javac, debugger, Javadoc).

Used by developers to write, compile, and run programs.

Without JDK, you can’t compile Java code.

## Usage

Open the **CCRMApp.java** in the src/edu/ccrm folder and run 
`javac CCRMApp.java`
then 
`java CCRMApp`

## Installation

![alt text](https://www.eclipse.org/downloads/packages/modules/custom/eclipsefdn/eclipsefdn_packages/images/installer-instructions-02.png)

![alt_text](https://www.eclipse.org/downloads/packages/modules/custom/eclipsefdn/eclipsefdn_packages/images/installer-instructions-03.png)

![alt_text](https://www.eclipse.org/downloads/packages/modules/custom/eclipsefdn/eclipsefdn_packages/images/installer-instructions-04.png)

![alt_text](https://www.eclipse.org/downloads/packages/modules/custom/eclipsefdn/eclipsefdn_packages/images/installer-instructions-05.png)

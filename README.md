This article is about the object-oriented programming language. For the software platform, see Java (software platform). For the Indonesian island, see Java. For the Indonesian Language, see Javanese. For other uses, see Java (disambiguation).
Not to be confused with JavaScript.
"Openframe" redirects here. For the ten-pin bowling term, see Open frame.
Java

Paradigm	Multi-paradigm: generic, object-oriented (class-based), functional, imperative, reflective, concurrent
Designed by	James Gosling
Developer	Oracle Corporation
First appeared	May 23, 1995; 30 years ago[1]
Stable release	
Java SE 24[2][3] Edit this on Wikidata / 18 March 2025; 6 months ago
Typing discipline	Static, strong, safe, nominative, manifest
Memory management	Garbage-collected
Filename extensions	.java, .class, .jar, .jmod, .war
Website	
oracle.com/java/
java.com
dev.java
Influenced by
CLU,[4] Simula67,[4] Lisp,[4] Smalltalk,[4] Ada 83, C++,[5] C#,[6] Eiffel,[7] Mesa,[8] Modula-3,[9] Oberon,[10] Objective-C,[11] UCSD Pascal,[12][13] Object Pascal[14]
Influenced
Ada 2005, ArkTS, BeanShell, C#, Chapel,[15] Clojure, ECMAScript, Fantom, Gambas,[16] Groovy, Hack,[17] Haxe, J#, JavaScript, JS++, Kotlin, PHP, Python, Scala, Vala
 Java Programming at Wikibooks
Java is a high-level, general-purpose, memory-safe, object-oriented programming language. It is intended to let programmers write once, run anywhere (WORA),[18] meaning that compiled Java code can run on all platforms that support Java without the need to recompile.[19] Java applications are typically compiled to bytecode that can run on any Java virtual machine (JVM) regardless of the underlying computer architecture. The syntax of Java is similar to C and C++, but has fewer low-level facilities than either of them. The Java runtime provides dynamic capabilities (such as reflection and runtime code modification) that are typically not available in traditional compiled languages.

Java gained popularity shortly after its release, and has been a popular programming language since then.[20] Java was the third most popular programming language in 2022 according to GitHub.[21] Although still widely popular, there has been a gradual decline in use of Java in recent years with other languages using JVM gaining popularity.[22]

Java was designed by James Gosling at Sun Microsystems. It was released in May 1995 as a core component of Sun's Java platform. The original and reference implementation Java compilers, virtual machines, and class libraries were released by Sun under proprietary licenses. As of May 2007, in compliance with the specifications of the Java Community Process, Sun had relicensed most of its Java technologies under the GPL-2.0-only license. Oracle, which bought Sun in 2010, offers its own HotSpot Java Virtual Machine. However, the official reference implementation is the OpenJDK JVM, which is open-source software used by most developers and is the default JVM for almost all Linux distributions.

Java 25 is the version current as of September 2025. Java 8, 11, 17, 21, and 25 are long-term support versions still under maintenance.

History
See also: Java (software platform) § History

Duke, the Java mascot

James Gosling, the creator of Java, in 2008
James Gosling, Mike Sheridan, and Patrick Naughton initiated the Java language project in June 1991.[23] Java was originally designed for interactive television, but it was too advanced for the digital cable television industry at the time.[24] The language was initially called Oak after an oak tree that stood outside Gosling's office. Later the project went by the name Green and was finally renamed Java, from Java coffee, a type of coffee from Indonesia.[25] Gosling designed Java with a C/C++-style syntax that system and application programmers would find familiar.[26]

Sun Microsystems released the first public implementation as Java 1.0 in 1996.[27] It promised write once, run anywhere (WORA) functionality, providing no-cost run-times on popular platforms. Fairly secure and featuring configurable security, it allowed network- and file-access restrictions. Major web browsers soon incorporated the ability to run Java applets within web pages, and Java quickly became popular. The Java 1.0 compiler was re-written in Java by Arthur van Hoff to comply strictly with the Java 1.0 language specification.[28] With the advent of Java 2 (released initially as J2SE 1.2 in December 1998 – 1999), new versions had multiple configurations built for different types of platforms. J2EE included technologies and APIs for enterprise applications typically run in server environments, while J2ME featured APIs optimized for mobile applications. The desktop version was renamed J2SE. In 2006, for marketing purposes, Sun renamed new J2 versions as Java EE, Java ME, and Java SE, respectively.

In 1997, Sun Microsystems approached the ISO/IEC JTC 1 standards body and later the Ecma International to formalize Java, but it soon withdrew from the process.[29][30][31] Java remains a de facto standard, controlled through the Java Community Process.[32] At one time, Sun made most of its Java implementations available without charge, despite their proprietary software status. Sun generated revenue from Java through the selling of licenses for specialized products such as the Java Enterprise System.

On November 13, 2006, Sun released much of its Java virtual machine (JVM) as free and open-source software (FOSS), under the terms of the GPL-2.0-only license. On May 8, 2007, Sun finished the process, making all of its JVM's core code available under free software/open-source distribution terms, aside from a small portion of code to which Sun did not hold the copyright.[33]

Sun's vice-president Rich Green said that Sun's ideal role with regard to Java was as an evangelist.[34] Following Oracle Corporation's acquisition of Sun Microsystems in 2009–10, Oracle has described itself as the steward of Java technology with a relentless commitment to fostering a community of participation and transparency.[35] This did not prevent Oracle from filing a lawsuit against Google shortly after that for using Java inside the Android SDK (see the Android section).

On April 2, 2010, James Gosling resigned from Oracle.[36]

In January 2016, Oracle announced that Java run-time environments based on JDK 9 will discontinue the browser plugin.[37]

Java software runs on most devices from laptops to data centers, game consoles to scientific supercomputers.[38]

Oracle (and others) highly recommend uninstalling outdated and unsupported versions of Java, due to unresolved security issues in older versions.[39]

Principles
There were five primary goals in creating the Java language:[19]

It must be simple, object-oriented, and familiar.
It must be robust and secure.
It must be architecture-neutral and portable.
It must execute with high performance.
It must be interpreted, threaded, and dynamic.
Versions
Main article: Java version history
As of September 2025, Java 8, 11, 17, 21, and 25 are supported as long-term support (LTS) versions.[40]

Oracle released the last zero-cost public update for the legacy version Java 8 LTS in January 2019 for commercial use, although it will otherwise still support Java 8 with public updates for personal use indefinitely. Other vendors such as Adoptium continue to offer free builds of OpenJDK's long-term support (LTS) versions. These builds may include additional security patches and bug fixes.[41]

Major release versions of Java, along with their release dates:

Version	Date
JDK Beta	1995
JDK 1.0	January 23, 1996[42]
JDK 1.1	February 19, 1997
J2SE 1.2	December 8, 1998
J2SE 1.3	May 8, 2000
J2SE 1.4	February 6, 2002
J2SE 5.0	September 30, 2004
Java SE 6	December 11, 2006
Java SE 7	July 28, 2011
Java SE 8 (LTS)	March 18, 2014
Java SE 9	September 21, 2017
Java SE 10	March 20, 2018
Java SE 11 (LTS)	September 25, 2018[43]
Java SE 12	March 19, 2019
Java SE 13	September 17, 2019
Java SE 14	March 17, 2020
Java SE 15	September 15, 2020[44]
Java SE 16	March 16, 2021
Java SE 17 (LTS)	September 14, 2021
Java SE 18	March 22, 2022
Java SE 19	September 20, 2022
Java SE 20	March 21, 2023
Java SE 21 (LTS)	September 19, 2023[45]
Java SE 22	March 19, 2024
Java SE 23	September 17, 2024
Java SE 24	18 March 2025[46]
Java SE 25 (LTS)	16 September 2025[47]
Editions
See also: Free Java implementations § Class library
Java platform editions

Java Card
Java ME (Micro Edition)
Java SE (Standard Edition)
Jakarta EE (Enterprise Edition)
JavaFX (bundled in Oracle's JDK from versions 8 to 10 but separately since 11)
PersonalJava (Discontinued)
vte
Sun has defined and supports four editions of Java targeting different application environments and segmented many of its APIs so that they belong to one of the platforms. The platforms are:

Java Card for smart-cards.[48]
Java Platform, Micro Edition (Java ME) – targeting environments with limited resources.[49]
Java Platform, Standard Edition (Java SE) – targeting workstation environments.[50]
Java Platform, Enterprise Edition (Java EE) – targeting large distributed enterprise or Internet environments.[51]
The classes in the Java APIs are organized into separate groups called packages. Each package contains a set of related interfaces, classes, subpackages and exceptions.

Sun also provided an edition called Personal Java that has been superseded by later, standards-based Java ME configuration-profile pairings.

Execution system

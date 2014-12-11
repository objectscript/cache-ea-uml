cache-ea-uml
============

Provides Export/Import tools from Caché to UML Enterprise Architect

Installation
==
1. Make Cachelib database read-write. (SMP → System Administration → Configuration → System Configuration → Local Databases, choose CACHELIB, uncheck Read Only, Save changes)
2. Import EA.xml files into SYS namespace
3. Compile imported classes
4. Make Cachelib database read-only (optional but recommended, see 1 for how-to)

Usage
==
1. Create UML class diagramm in UML editor (tested on Enterprise Architect)
2. Export it as XMI 2.1 file
3. In Caché Studio import file it via Tools → Add Ins → Extensions → Import UML Diagram

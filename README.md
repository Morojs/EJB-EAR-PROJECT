# EJB-EAR-PROJECT
Exemple d'Enterprise Java Beans (EJB)
==============

Cet exemple illustre l'injection d'un EJB dans un servlet. L'application se compose d'un ensemble de servlets et d'un bean de session sans état. Le servlet utilise des annotations. pour injecter le bean session sans état, puis effectue un appel sur des methodes.

Cet exemple utilise wildfly qui fait appel à un instance d'une base de données mysql en docker [PORT:3307:3306]

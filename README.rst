sqlite3.buildout
================

Configuración de buildout para el compilar e instalar SQLite3

Requerimientos
==============

Estos son los requerimientos mínimos de instalación: ::

  aptitude install gcc g++ make tar unzip bzip2 libssl-dev libxml2-dev zlib1g-dev libjpeg62-dev libreadline6-dev readline-common wv xpdf-utils python2.7-dev libxslt1-dev

Inicialización del proyecto
===========================

Para la inicialización del proyecto Buildout, ejecute el siguiente comando: ::

  python bootstrap.py

Construcción del proyecto
=========================

Para la construcción del proyecto Buildout, ejecute el siguiente comando: ::

  ./bin/buildout

Ejecutar SQLite3
================

Para ejecutar la base de datos SQLite3, ejecute el siguiente comando: ::

  ./bin/sqlite3

SQLite3 en Python
=================

Para manipular la base de datos SQLite3 en lenguaje programacion Python, ejecute el siguiente comando: ::

  ./bin/ipy-sqlite
  >>> from pysqlite2 import dbapi2 as sqlite3
  >>> sqlite3.sqlite_version
  '3.8.2'

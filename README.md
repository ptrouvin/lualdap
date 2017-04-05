*LuaLDAP
LUA LDAP interface, fork from
(https://github.com/luaforge/lualdap)
(http://www.keplerproject.org/lualdap/)

LuaLDAP is a simple interface from Lua to an LDAP client, in fact it is a bind to
OpenLDAP or to ADSI. It enables a Lua program to:

    * Connect to an LDAP server;
    * Execute any operation (search, add, compare, delete, modify and rename);
    * Retrieve entries and references of the search result.

LuaLDAP is free software and uses the same license as Lua 5.1.

Current version is 1.1. It was developed for both Lua 5.0 and Lua 5.1,
and both OpenLDAP 2.1 or newer and ADSI.

Files in the distribution:

    /doc/us/*.html  -- Documentation
	/src/*			-- Source files
	/tests/*        -- Test files
	/vc6/*          -- Build files for MS Visual C 6 (deprecated)
    Makefile        -- Makefile for Unix systems
    config          -- Configurations to build on Unix systems
    Makefile.win    -- Makefile for Windows systens with MS Visual C 8
    config.win      -- Configurations to build on Windows systems
    README          -- This file

$Id: README,v 1.7 2007-12-14 15:14:54 carregal Exp $

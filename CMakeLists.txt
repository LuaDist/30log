# Copyright (C) 2007-2013 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( 30log NONE )
cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )
include ( lua )

install_lua_module ( 30log 30log.lua )
install_lua_module ( 30logclasscommons 30logclasscommons.lua )
install_lua_module ( 30logclean 30logclean.lua )
install_lua_module ( 30logglobal 30logglobal.lua )

install_test ( tests/ )
install_data ( LICENSE README.md )

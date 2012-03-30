# Copyright (C) 2007-2012 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( tlc C )
cmake_minimum_required ( VERSION 2.6 )
include ( dist.cmake )

install_lua_module ( objc objc.lua )
install_doc ( README.md )
install_example ( examples/ )

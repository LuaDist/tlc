# Copyright (C) 2012 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( tlc NONE )
cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )
include ( lua )

install_lua_module ( objc.init objc/init.lua )
install_lua_module ( objc.BridgeSupport objc/BridgeSupport.lua )
install_doc ( README.md )
install_example ( examples/ )

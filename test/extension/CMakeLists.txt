#
# Copyright (c) 2019 Mateusz Loskot <mateusz at loskot dot net>
#
# Distributed under the Boost Software License, Version 1.0.
# (See accompanying file LICENSE_1_0.txt or copy at
# http://www.boost.org/LICENSE_1_0.txt)
#
if(GIL_ENABLE_EXT_NUMERIC)
  add_subdirectory(numeric)
endif()

if(GIL_ENABLE_EXT_TOOLBOX)
  add_subdirectory(toolbox)
endif()

if(GIL_ENABLE_EXT_IO)
  add_subdirectory(io)
endif()

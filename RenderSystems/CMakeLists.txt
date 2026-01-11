#-------------------------------------------------------------------
# This file is part of the CMake build system for OGRE
#     (Object-oriented Graphics Rendering Engine)
# For the latest info, see http://www.ogre3d.org/
#
# The contents of this file are placed in the public domain. Feel
# free to make use of it in any way you like.
#-------------------------------------------------------------------

# Configure RenderSystem build - D3D9 and D3D11 only

if (OGRE_BUILD_RENDERSYSTEM_D3D9)
  add_subdirectory(Direct3D9)
endif ()

if (OGRE_BUILD_RENDERSYSTEM_D3D11)
  add_subdirectory(Direct3D11)
endif ()

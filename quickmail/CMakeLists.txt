set(COMPONENT_SRCS
  quickmail.c
  )

set(COMPONENT_ADD_INCLUDEDIRS 
  . 
  )
  
set(COMPONENT_REQUIRES curl)

register_component()

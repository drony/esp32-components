set(COMPONENT_SRCS
  adler32.c
  compress.c
  crc32.c
  deflate.c
  gzclose.c
  gzlib.c
  gzread.c
  gzwrite.c
  infback.c
  inffast.c
  inflate.c
  inftrees.c
  trees.c
  uncompr.c
  zutil.c
  )

set(COMPONENT_ADD_INCLUDEDIRS .)

set(COMPONENT_PRIV_INCLUDEDIRS .)

register_component()

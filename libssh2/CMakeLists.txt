set(COMPONENT_SRCS
  src/misc.c
  src/openssl.c
  src/agent.c
  src/wincng.c
  src/kex.c
  src/global.c
  src/keepalive.c
  src/knownhost.c
  src/packet.c
  src/crypt.c
  src/mbedtls.c
  src/comp.c
  src/hostkey.c
  src/mac.c
  src/libgcrypt.c
  src/userauth.c
  src/transport.c
  src/version.c
  src/session.c
  src/scp.c
  src/channel.c
  src/publickey.c
  src/sftp.c
  src/pem.c
  src/os400qc3.c
  )

set(COMPONENT_ADD_INCLUDEDIRS 
  include 
  )

set(COMPONENT_PRIV_INCLUDEDIRS 
  src 
  )

set(COMPONENT_REQUIRES mbedtls)

register_component()

FILE(GLOB RAWSPEED_FUZZ_SOURCES
  "Common.cpp"
  "Common.h"
  "RawSpeed.cpp"
)

target_sources(rawspeed_fuzz PRIVATE
  ${RAWSPEED_FUZZ_SOURCES}
)

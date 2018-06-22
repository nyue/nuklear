# Compile
ADD_EXECUTABLE ( canvas
  canvas.c
  )

ADD_EXECUTABLE ( extended
  extended.c
  )

ADD_EXECUTABLE ( file_browser
  file_browser.c
  )

ADD_EXECUTABLE ( skinning
  skinning.c
  )

# Link
TARGET_LINK_LIBRARIES ( canvas
  ${NUKLEAR_REQUIRED_LINK_LIBRARIES}
  )

TARGET_LINK_LIBRARIES ( extended
  ${NUKLEAR_REQUIRED_LINK_LIBRARIES}
  )

TARGET_LINK_LIBRARIES ( file_browser
  ${NUKLEAR_REQUIRED_LINK_LIBRARIES}
  )

TARGET_LINK_LIBRARIES ( skinning
  ${NUKLEAR_REQUIRED_LINK_LIBRARIES}
  )

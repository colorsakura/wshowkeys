inc = include_directories('.')

executable(
  'wshowkeys',
  files(
    'devmgr.c',
    'main.c',
    'pango.c',
    'shm.c',
  ),
  include_directories: inc,
  dependencies: [
    cairo,
    client_protos,
    libinput,
    pango,
    pangocairo,
    rt,
    udev,
    wayland_client,
    wayland_protos,
    xkbcommon,
  ],
  install: true,
)

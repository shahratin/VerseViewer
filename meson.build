project('VerseViewerGtk', 'vala', 'c')

sources = files(
  'VerseViewerGtk.vala',
)

dependencies = [
  dependency('gio-2.0'),
  dependency('glib-2.0'),
  dependency('gobject-2.0'),
  dependency('gstreamer-1.0'),
  dependency('gtk4'),
]

executable(
  meson.project_name(),
  sources,
  dependencies: dependencies,
  install: true
)

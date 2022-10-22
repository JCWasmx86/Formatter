foobar_sources = [
  'main.vala',
  'application.vala',
  'window.vala',
]

foobar_deps = [
  dependency('gtk4'),
  dependency('libadwaita-1'),
]

foobar_sources += gnome.compile_resources('foobar-resources',
  'foobar.gresource.xml',
  c_name: 'foobar'
)

executable('foobar', foobar_sources,
  dependencies: foobar_deps,
       install: true,
)

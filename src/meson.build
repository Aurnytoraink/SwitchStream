moduledir = join_paths(pkgdatadir, 'switchstream')

configure_file(
  input: 'switchstream.in',
  output: 'switchstream',
  configuration: conf,
  install: true,
  install_dir: get_option('bindir')
)

switchstream_sources = [
  '__init__.py',
  'main.py',
  'window.py',
]

install_data(switchstream_sources, install_dir: moduledir)

project(
  'wallpapers-alt-mobile-sisyphus',
  version: '0.1.0',
  meson_version: '>= 0.50.0',
)

i18n = import('i18n')

prefix = get_option('prefix')

datadir = join_paths(prefix, get_option('datadir'))
backgrounddir = join_paths(datadir, 'wallpapers', 'alt-mobile')
metadatadir = join_paths(datadir, 'gnome-background-properties')

subdir('wallpapers')

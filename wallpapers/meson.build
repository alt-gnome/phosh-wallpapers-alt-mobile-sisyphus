conf = configuration_data()
conf.set('BACKGROUNDDIR', backgrounddir)
conf.set('datadir', datadir)

backgrounds = [
  'hex-black-ld.png',
]

metadatas = [
  'alt-mobile-hex-black.xml',
]

install_data(backgrounds, install_dir: backgrounddir)

foreach metadata : metadatas
  configure_file(
    input: metadata + '.in',
    output: metadata,
    configuration: conf,
    install: true,
    install_dir: metadatadir,
  )
endforeach

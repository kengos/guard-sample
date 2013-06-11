guard 'coffeescript', input: 'assets/coffee', output: 'public/javascripts'
guard 'sass', input: 'assets/sass', compass: true, output: 'public/css', compress: true, style: :compressed
guard 'sprockets', destination: 'public/javascripts', asset_paths: ['assets/javascripts'], minify: true do
  watch(%r{^assets/javascripts/([^/]*)\.js$})
end
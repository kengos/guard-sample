guard 'coffeescript', :input => 'assets/coffee'
guard 'sass', input: 'assets/sass', output: 'public/css', compress: true
guard 'sprockets', destination: 'public/javascripts', asset_paths: ['assets/javascripts'], minify: true do
  watch(%r{^assets/javascripts/([^/]*)\.js$})
end
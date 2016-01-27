task :jslint do
  system "node_modules/.bin/jslint lib/*.js"
end

task :mocha do
  system "node_modules/.bin/mocha spec/*.js"
end

task default: [:jslint, :mocha]

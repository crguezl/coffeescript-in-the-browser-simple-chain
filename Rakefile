desc "Compile all coffee files in src/i and leave the translation in public/js"
task :default do
  sh "coffee -co public/js -w src"
end

desc "install http-server -g"
task :installserver do
  sh "npm install http-server -g"
end

desc "open index.html"
task :open do
  sh "open http://localhost:8080/index.html"
end

desc "run http-server"
task :server do
  sh "http-server"
end


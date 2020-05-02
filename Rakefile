
desc 'build the jekyll app'
task :build do
  sh "jekyll build"
end

desc 'serve the jekyll app at localhost:4000'
task :start do
  sh "jekyll serve"
end

desc "default is build only"
task :default  => [ :build ]

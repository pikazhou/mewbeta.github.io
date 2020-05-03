
desc 'build the jekyll app'
task :build do
  sh "bundle exec jekyll build --trace"
end

desc 'serve the jekyll app at localhost:4000'
task :start do
  sh "bundle exec jekyll serve"
end

desc "default is build only"
task :default  => [ :build ]

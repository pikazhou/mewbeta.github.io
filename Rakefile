
desc 'build the jekyll app'
task :build do
  sh "bundle exec jekyll build --trace"
end

desc 'clean _site'
task :clean do
  sh "rm -rf _site"
end

desc 'jekyll doctor'
task :check do
  sh "bundle exec jekyll doctor"
end
desc 'serve the jekyll app at localhost:4000'
task :start do
  sh "bundle exec jekyll serve"
end

desc "default is build only"
task :default  => [ :build ]

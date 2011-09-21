task :default => :serve

desc "Start serving the presentation on localhost:9090" 
task :serve do
  sh "bundle exec showoff serve"
end

desc "Install necessary ruby gems to support the presentation"
task :install do
  sh "bundle install"
end

desc "Generate static version"
task :static do
  sh "bundle exec showoff static"
end

desc "Checkout the SVN sample repo"
task :svn_co do
  mkdir_p "hideaway"
  cd "hideaway" do
    sh "svn co https://svn.atomicobject.com/svn/crosby/esc"
  end
end

task :build => :static

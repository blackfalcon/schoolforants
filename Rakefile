desc "Run the development server"
task :server do
  exec "bundle exec compass compile && bundle exec ruby app.rb -p 3000"
end

desc "Compile the app's Sass"
task "assets:precompile" do
  system("jammit --force")
  system("compass compile")
end
desc "Gist It!"
task :gist do
  files = `ls | grep -Ev "package.json|Gemfile|node_modules|Procfile|Guardfile|Rakefile" | tr "\\n" " "`
  sh "gist -c  #{files}"

end

desc "Gist login"
task :gist_login do
  sh "gist --login"
end

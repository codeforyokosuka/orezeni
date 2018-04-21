task :default => [:preview]

# Usage: rake preveiw
desc "Launch preview environment"
task :preview do
	sh "jekyll --server --auto"
end

# Usage: rake build
desc "Build Jekyll static pages"
task :build do
	sh "jekyll build"
end

desc "deploy GitHub:Pages"
task :deploy do
	sh "git checkout master"
	sh "git push -f git@github.com:orezeni/orezeni.github.com.git master"
end

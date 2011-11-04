source :rubygems

gem "rake"

%w[rspec-expectations rspec-mocks].each do |lib|
  gem lib, :path => File.expand_path("../../#{lib}", __FILE__)
end

gem "rspec-core", git: "git://github.com/rodrigues/rspec-core.git"
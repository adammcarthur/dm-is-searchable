require 'rubygems'
require 'rake'

begin
  gem 'jeweler', '~> 1.6.4'
  require 'jeweler'

  Jeweler::Tasks.new do |gem|
    gem.name        = 'dm-is-searchable'
    gem.summary     = 'A DataMapper plugin for searching'
    gem.description = gem.summary
    gem.email       = 'bernerd [a] wieck [d] com'
    gem.homepage    = 'http://github.com/datamapper/%s' % gem.name
    gem.authors     = [ 'Bernerd Schaefer' ]
    gem.has_rdoc    = 'yard'

    gem.rubyforge_project = 'datamapper'
  end

  Jeweler::GemcutterTasks.new

  FileList['tasks/**/*.rake'].each { |task| import task }
rescue LoadError
  puts 'Jeweler (or a dependency) not available. Install it with: gem install jeweler'
end

require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('string-utils', '0.2.1') do |p|
  p.description    = "This small extension enables string sanitization in models and controller. Provides also a function for making url friendly strings removing all unwanted characters."
  p.url            = "http://github.com/hanloong/string-utils"
  p.author         = "Han Loong Liauw"
  p.email          = "hanloongliauw@gmail.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }

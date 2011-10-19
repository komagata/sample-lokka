$:.unshift File.join(File.dirname(__FILE__), 'lokka', 'lib')
require 'lokka'

desc 'Setup Lokka'
task 'setup' do
  Lokka::Database.new.connect.setup
end

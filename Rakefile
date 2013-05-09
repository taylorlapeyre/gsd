require 'rake'

task :default => [:install]

task :install do
  destination  = ""
  destinations = ["/usr/local/bin", "#{Dir.home}/bin", "#{Dir.home}/home/bin"]
  
  destinations.each do |location|
    destination = location if Dir.exists?(location)
  end
    
  FileUtils.install "gsd", "#{destination}/gsd", :mode => 0755, :verbose => true
  FileUtils.install "distraction_sites", "#{destination}/distraction_sites", :mode => 0755, :verbose => true
end

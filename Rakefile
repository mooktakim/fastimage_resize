require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |s|
    s.name = "fastimage_resize"
    s.summary = "FastImage Resize - Image resizing fast and simple"
    s.email = "sdsykes@gmail.com"
    s.homepage = "http://github.com/sdsykes/fastimage_resize"
    s.description = "FastImage Rssize is an extremely light solution for resizing images in ruby by using libgd."
    s.authors = ["Stephen Sykes"]
    s.files = FileList["[A-Z]*", "{lib,test}/**/*"]
    s.requirements << 'libgd, see www.libgd.org'
    s.add_dependency('RubyInline', '>= 3.8.2')
    s.add_dependency('sdsykes-fastimage', '>= 1.1.2')
  end
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://
gems.github.com"
end

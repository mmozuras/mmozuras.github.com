#!/usr/bin/env rake
desc 'preview blog'
task preview: [:clean, :sass] do
  system('jekyll serve')
end

desc 'clean site'
task :clean do
  `rm -rf _site`
  puts 'Removed _site directory'
end

desc 'convert sass files to css'
task :sass do
  unless File.directory?('assets/css')
    Dir.mkdir('assets/css')
    puts 'Created /assets/css directory'
  end

  `sass --style compressed assets/sass/default.scss > assets/css/default.css`
  puts 'Converted Sass to Css'
end

task default: :preview

desc 'preview blog'
task :preview => [:clean, :sass] do
  `jekyll --auto --server`
end

desc 'clean site'
task :clean do
  `rm -rf _site`
  puts 'Removed _site directory'
end

desc 'convert sass files to css'
task :sass do
  if not File.directory?('static')
    Dir.mkdir('static')
    puts 'Created /static directory'
  end

  `sass --style compressed _sass/default.sass > static/default.css`
  puts 'Converted Sass to Css'
end


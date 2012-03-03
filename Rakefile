desc 'convert sass files to css'
task :sass do
  if not File.directory?('css')
    Dir.mkdir('css')
    puts 'Created /css directory'
  end

  puts 'Converting Sass to Css'
  `sass --style compressed _sass/default.sass > css/default.css`
  puts 'Done'
end

require 'yaml'
require 'rake/clean'
CLEAN.include '*.json'

namespace :test do
  task :links2 do
    require 'awesome_bot'
    content = File.read('readme.md')
    result = AwesomeBot.check(content)
    puts result.success(nil) ? ':)' : ':('
  end

  CMD_STRING = YAML.load_file('.travis.yml')['script']
  desc 'Test links with AwesomeBot.'
  task :links do
    system(CMD_STRING)
  end
end

desc 'Regenerate the TOC.'
task :toc do
  `node_modules/markdown-toc/cli.js -i readme.md`
end

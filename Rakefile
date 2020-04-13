require 'pdksync/rake_tasks'

desc 'validate managed modules'
task :validate do
  require 'yaml'
  mods = YAML.load_file('managed_modules.yml').count
  mods > 0 ? exit(0) : exit(1)
end

# guard 'coffeescript', :input => 'src', :output => 'chrome/js'

# guard 'sass', :input => 'src', :output => './build/css'

# Sample guardfile block for Guard::Haml
# You can use some options to change guard-haml configuration
# :output => 'public'                   set output directory for compiled files
# :input => 'src'                       set input directory with haml files
# :run_at_start => true                 compile files when guard starts
# :notifications => true                send notifictions to Growl/libnotify/Notifu
# :haml_options => { :ugly => true }    pass options to the Haml engine

require './helpers'

guard 'haml', run_at_start: true, input: 'src', output: 'build' do
  watch(/^.+(\.haml)/)
end

guard :copy, run_at_start: true, from: 'public', to: 'build' 


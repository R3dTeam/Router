workspace 'Router'
project 'Router'
project 'RouterExample'

use_frameworks!

def testing_pods
  pod 'Quick', '~> 0.10.0'
  pod 'Nimble', '3.0.0'
end

target 'RouterTests' do
  testing_pods
  project 'Router'
end

target 'RouterExampleTests' do
  testing_pods
  project 'RouterExample'
end

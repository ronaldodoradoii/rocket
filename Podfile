# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

def test_pods
  pod 'Nimble', '7.3.1'
end

target 'groot' do
  use_frameworks!

  pod 'SnapKit', '4.2.0'

  target 'grootTests' do
    inherit! :search_paths
    test_pods
  end

  target 'grootUITests' do
    inherit! :search_paths
    test_pods
  end
end



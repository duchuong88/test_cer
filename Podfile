# Uncomment the next line to define a global platform for your project
platform :ios, '10.0'

target 'Cser2022' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
pod 'Firebase/Core'
pod 'Firebase/Messaging'
pod 'Alamofire'

post_install do |installer|
    installer.generated_projects.each do |project|
        project.targets.each do |target|
            target.build_configurations.each do |config|
                config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '10.0'
            end
        end
    end
end

  # Pods for Cser2022

  target 'Cser2022Tests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'Cser2022UITests' do
    # Pods for testing
  end

end

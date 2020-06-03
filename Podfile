use_frameworks!

def shared_pods
    pod 'CoreGPX'
end

target 'CleanUp' do
    platform :ios, '8.0'
    shared_pods
    pod 'MapCache', '~> 0.6.0'
    #pod 'MapCache', git: 'https://github.com/merlos/MapCache.git' :branch => 'master'
    
end

target 'CleanUp-Watch Extension' do
    platform :watchos, '2.0'
    shared_pods
end

---
layout: page
title: Max working at React Native
permalink: /projects/react-native
excerpt:
tags: learn no-index
---
  
### Getting Started  
Read more at [React Native](https://facebook.github.io/react-native/docs/getting-started.html#content)

1. install  
    > # npm install -g react-native-cli
    
2. run (init)
    > \# react-native init Max123  
    > \# cd AwesomeProject  
    > \# react-native run-ios  
    
3. coding  
    > # vi index.ios.js 
    
### Add iBeacon support (iOS)  
Read more at [react-native-ibeacon](https://github.com/frostney/react-native-ibeacon)  

1. install  
    > \# npm install --save react-native-ibeacon
2. Compile  
    >You then need to add the Objective C part to your XCode project. Drag RNBeacon.xcodeproj from the node_modules/react-native-ibeacon folder into your XCode project. Click on the your project in XCode, goto Build Phases then Link Binary With Libraries and add libRNBeacon.a and CoreLocation.framework.  
    
        ![XCode - BG](/images/projects/react-native/xcode-bg.png)  
        
        ![XCode - LINK](/images/projects/react-native/xcode-link.png)    

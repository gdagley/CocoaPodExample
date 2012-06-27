This an example project to show off CocoaPods

## Dependency Management: ##

* Java: Maven
* Ruby: Bundler
* iOS: ?

## CocoaPods ##

http://cocoapods.org

## Installation ##

    $ [sudo] gem install cocoapods --pre
    $ pod setup

Create an xcode project: CocoaPodExample

Close Xcode

    $ cd /path/to/CocoaPodExample
    $ mate Podfile

Contents of Podfile

    platform :ios
    xcodeproj 'CocoaPodExample.xcodeproj'

    dependency 'JSONKit',           '~> 1.4'

Back on the commandline

    $ pod install CocoaPodExample.xcodeproj
    $ open CocoaPodExample.xcworkspace

Add to Podfile

    dependency 'ConciseKit',           '~> 0.1.2'

Back on the commandline

    $ pod install

Refresh Xcode workspace

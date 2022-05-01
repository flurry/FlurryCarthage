# FlurryCarthage



   1. See here for instructions to install Carthage: https://github.com/Carthage/Carthage

   2. Create a Cartfile in the same directory where your .xcodeproj or .xcworkspace is

   3. List the desired dependencies in the Cartfile, for example:

    github "flurry/FlurryCarthage" ~> 12.0.0

   4. Run carthage update --use-xcframeworks

    A Cartfile.resolved file and a Carthage directory will appear in the same directory where your .xcodeproj or .xcworkspace is

   5. Drag the built .xcframework bundles from Carthage/Build into the "Frameworks and Libraries" section of your application’s Xcode project.

   6. If you are using Carthage for an application, select "Embed & Sign", otherwise "Do Not Embed".

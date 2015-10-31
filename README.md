# CarthagePlayground
Carthage dependency manager Playground


In order for the framework to work within a playground, the project that produces the framework must be included in the workspace for your project. So to make this work you need to follow these steps:

1) If your project is not inside a workspace, create a workspace for your project by choosing File > Save As Workspace in Xcode.

2) Drag the .xcodeproj file from the Carthage/Checkouts folder into your workspace.

3) Run the build action on your framework target.


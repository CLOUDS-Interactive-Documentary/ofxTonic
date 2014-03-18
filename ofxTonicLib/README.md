# ofxTonicLib

The shared lib approach is a convenient way of working with large blocks of code in Visual Studio.

To use this in your project:

1. Create an empty project (do not select ofxTonic or its dependencies in project generator)
2. Add the `ofxTonicLib` project to your solution
3. Go to 'Property Manager', right click on your project and add select 'Add existing property sheet...', select `ofxTonic.props`
3. Go to your project properties, go to 'Common Properties' on the left, select 'Add New Reference...' and select the ofxTonicLib project
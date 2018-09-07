# Boarding Pass


> ## Constraint Layout 

- Constraint layout allows you to create a complex layout without having to nest view groups inside each other.

- It is much similar to Relative layout where each constraint represents a connection or alignment to another view or to the parent layout.

- The underlying structure of Constraint-layout is much simpler and hence, it usually outperforms the other layout.  
 

:pushpin: dependencies {
         compile 'com.android.support.constraint:constraint-layout:1.0.0-beta4'
 }




> ## Data Binding

- This library can help us link any UI with actual data without having to call findViewById() for every view.

- Steps : 

1. Enable data binding in build.gradle.

2. Add <layout> root tag to the Ui.

3. Create binding instance.

4. Set the content-view using DatabindingUtil.

5. Bind each attribute in the views to the corresponding data.

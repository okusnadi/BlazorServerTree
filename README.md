# BlazorServerTree

A simple Server-Side Blazor sample app to deal with hierarchical data.

The project has a fake data layer service that allow running it without database backend configuration.

The basic functionality is ready:

* Unexpand nodes and expand nodes with Lazy load.
* Select and unselect a node.

Code ( code is my friend )

```
    <UITreeComponent SourceData=@uiTree
                     SelectChangeDelegate=@OnSelectionChanged
                     LazyLoadNodesAsyncDelegate=@LoadNodes
                     CollapseAsyncDelegate=@OnCollapse
                     ExpandAsyncDelegate=@OnExpand
                     TriggerActionAsyncDelegate=@OnAction>
    </UITreeComponent>  
```

Screenshot ( because all us love screenshots ):

![screenshot](./screenshots/screenshot_smallv2.gif)

Don't hesitate to contact me for further information :)


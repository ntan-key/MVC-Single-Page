# MVC-Single-Page

This LabVIEW project contains the following classes:

![Class Diagram](https://github.com/ntan-key/MVC-Single-Page/blob/main/Docs/ClassDiagram.png)

## Launcher

The entry point to the application is `Application > Launcher.vi`. This runs the following VI's in sequence:

1. `View:Create.vi`: This creates a new `View` object which creates a new `Controller` object which creates a new `Model` object.
2. `View:UI.vi`: This launches the main UI which has UI components (controls/indicators) on the front panel and contains the event handling loop.

## UI

![Front Panel](https://github.com/ntan-key/MVC-Single-Page/blob/main/Docs/FrontPanel.png)

The UI contains the following:
- `View:Integer` control: This can be used to change the value of Integer stored in the Model class private data.
- `Model:Integer` indicator: This displays the value of Integer returned by the Model.
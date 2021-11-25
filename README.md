# Angular-Vertical-Tabs


## Usage

See [example](src/app). Only difference in your app is your imports:

    import { MaterialTabsModule } from 'angular-vertical-material-tabs/dist/material-tabs';
    
    // add it to the `imports:` of your relevant `@NgModule`
    imports: [ MaterialTabsModule.forRoot() ]

Then in your template:

    <ng-vertical-material-tabs [multi]=true [selectFirstTab]=false [showSelectAll]=true>
      <ng-vertical-material-tab tabTitle="Tab 0">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        Mauris tincidunt mattis neque lacinia dignissim.
        Morbi ex orci, bibendum et varius vel, porttitor et magna.
      </ng-vertical-material-tab>
    
      <ng-vertical-material-tab tabTitle="Tab b">
        Curabitur efficitur eleifend nulla, eget porta diam sodales in.
        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        Maecenas vestibulum libero lacus, et porta ex tincidunt quis.
      </ng-vertical-material-tab>
    
      <ng-vertical-material-tab tabTitle="Tab 2">
        Sed dictum, diam et vehicula sollicitudin, eros orci viverra diam, et pretium
        risus nisl eget ex. Integer lacinia commodo ipsum, sit amet consectetur magna
        hendrerit eu.
      </ng-vertical-material-tab>
    </ng-vertical-material-tabs>


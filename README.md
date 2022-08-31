# Angular Notes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.2.


## Choosing a angular functionality

You can choose the angular functionality you want to see, to do that, follow those steps:

1. First, look in ./src/app and open the funcionality folder name that you want
2. Go to component.ts file and copy what have in component selector option (you will see something like 'app-component-name')
3. In ./src/app look for app.component.html, open this file and paste between '</>' the component selector that you copy

Now we have the component that we want render in app.component.html: 
~~~html
<app-component-name><app-component-name/>
~~~
You can place as many components as you like to see.
~~~html
<app-component-name><app-component-name/>
<app-component-name2><app-component-name2/>
<app-component-name3><app-component-name3/>
~~~

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

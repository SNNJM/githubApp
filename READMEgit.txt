------PROJECT QUICKSTART-------
clone it from

git clone https://github.com/angular/quickstart 

then we will have angular 2 app codes ^_^

NOTE:
In your app.component.ts you define directive: [TodosComponent]. The directive property has been removed in RC6 from the @Component() decorator.

The solution to this, is to:

create an NgModule and
declare the TodosComponent inside the declarations: [] array.
See here for an example of AppModule:



-------APP TO DISPLAY GITHUB USERS & REPOS--------
# Basic Theming in Andriod With JetCompose and Material Design  

> Android uses Material theme by default. When a new project is created using Empty Compose Activity template, theme is also created. SetContent function contains theme, which is a composable containing all other composables in the app. By default, theme
contains one surface, which again contains a composable.
> 
>  Theme files are create under ui.theme package containing Theme, Color, Shape and Type Kotlin files. Those files contain default values, for example, causing a button to have a purple color, 4dp 
rounded edges, etc.
> 
>  This walkthrough demonstrates how default values can be changed to create your own theme.
>
> Theme has a lot of features, which can be changed. Basically, everything from Material 
Design (various colors, typefaces, shapes) can be changed to meet your design and 
theme.
> 
> It is a good practice to make all definitions concerning appearance to the theme file 
instead of making definitions all over the code. First, this gives a centralized place where 
all definitions are made, adds reusability and consistency. Theme also takes account 
light and dark modes.
>
>Theme can be also exported from various design tools. For example, Material design 3 
tool available on https://m3.material.io/theme-builder#/custom is able 
generate/export theme files compatible with Jetpack Compose
>
> ### Color Converter : https://convertingcolors.com/

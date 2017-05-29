# Color-Themes

Simple repository for Intellij and eclipse color themes, as all of the websites for that purpose I have found have disappointed.

The general strategy of the theme is as follows;
-The purpose of these themes is not to look nice but to make distinguishing different code constructs easy at a glance.
-Insofar as possible, try to reuse the same ideas in different languages (e.g. Javascript functions get the same color as Java methods)
-Prefer the same or slight variants on a color for construct that belong to the same category (e.g. constructor calls and normal class methods are both some shade of yellow)
-Prefer to use font features other than color for modifiers (e.g. italics for static methods and variables both)

Shared characteristics-

-Dark background. Obviously, these will all need to be reassigned for a light background.
-Italics = static
-Underlined = Constants
-Brighter shade = Deeper scope (e.g. the brighest will be a local variable)
-Language keyword = grey
-Operator = white
-Yellow = Functions/Methods/Subroutines
-Purple = Variables/constants
-Blue = Class/Interface Declaration
-Comment = Green
-String/number literal = Orange
-Red = Error
-Other/Language-specific = Middle-ground color (e.g. Teal)
--Java Annotations = Teal	

Java
-Bordered = Abstract or anonymous
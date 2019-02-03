This tex file generates both the non-solution and solution versions of the section notes by using
a boolean switch. The easiest thing to do is to render the solution, rename it, and then
render the non-solution. You have to do something like this because regardless of whether
the switch is set to true or false, the file renders with the same name and you would over-write
one by rendering the other without renaming.

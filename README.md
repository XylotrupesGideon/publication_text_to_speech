# PubScreenReader Converter
This project aimes to make scientific literature more accessible by rewriting publications in a way that they can be read by screen readers. This will not only allow visually impared people to read the newest scientific articles but it also allows the average scientist to listen to publications and thus increase their reading list.

##Planned Features

### Abbreviation reverse engenieering
Scientific publications are often full of abbreviations. These are easy for a reader to understand but in a screen reader these abbreviations are very cryptic and should be replaced with the log form of the world.
We need a detection mechanism for abbreviations and thier respectiv long forms.

### Reference manageing
While references are extremely important for scientific literature we need to handle a way to them from screen readers. References are usually ignored by readers except in the cases where particular interest to the reader.
In the first instance the references should therefore be removed from the text for casual reading. 
If references are required I would like to integrate them into the text flow by automatically inserting full sentences e.g. insttead of:

`This is a proven fact (Bergheim et al. 2022)`

generate something like:

`This is a proven fact, which was shown by Bergheim and collegues in 2012.`

### Figure legend recognition
We need a clear way to detect a figure legend in the text and separate it from the rest of the text. otherwise the text flow in most publications is very confusing when read out using a screen reader.

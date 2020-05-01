# MRE of ActiveStorage issue
Run this application, upload any file and hit "Save". The server will error with an error 500, saying
```
NameError (uninitialized constant #<Class:[reference]>::Analyzable
Did you mean?  ActiveStorage::Analyzer):
```
At least, it will if it's doing the same thing as it is on my computer!
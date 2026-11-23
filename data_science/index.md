
# Reimagined UI for Orange

I used **[Orange](https://orangedatamining.com/)** for learning in a more visual way in order to have a first glimpse of some algorithms. Almost no-code, but simple visualisation of a data processing pipeline.

But... you have to install it. Although the installation is simple, sometimes you wonder: what if it would have been a more moder web application?

That is where [red-orange](https://github.com/tasahi/red-orange) comes into play: a known framework such as [node-red](https://orangedatamining.com/) with extra features such as Orange Data Mining widgets. Sends the process to the backend, and the heavy lifting occurs there.

Of course other important points: the original node-red has its backend in **node** and Orange is in Python. One solution: create a API compatible version with Python/Fastapi. The basic backend implementation is [red-fastapi](https://github.com/tasahi/red-fastapi).

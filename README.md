# JavaScript lab 2
In this lab, you'll write some more JavaScript.

### 1. Clone the repo & Initialize

```
cd ~/Desktop/
git clone https://github.com/meet-projects/y2s17-d6-js2.git
cd y2s17-d6-js2/
source initialize.sh
```

Open all the files of the project in sublime text with this command:
```
subl .
```

Now, run the web server. 
```
flask run
```

Open up your browser and navigate to
[http://127.0.0.1:5000](http://127.0.0.1:5000).

### 2. Exercises

#### Exercise 1

Look through `templates/index.html` to find the IDs and classes of the
different `div` in the page.

Open the JavaScript console with Ctrl+Shift+J. Using [http://coolors.co/](http://coolors.co/),
jQuery selectors, and the `.css()` method, give the webpage a temporary
makeover with a better colorscheme. **Don't change the `site.css` file!**

Show your result to a TA or instructor before continuing.


#### Exercise 2

If you want, you can change `static/css/site.css` for the rest of the lab.

Open `static/js/script.js`. Notice that just like in the last lab, all
JavaScript code goes inside `$(document).ready(function() {`.

Add code so that when you click on the picture, the text in the box changes
from "We're almost halfway through MEET Y2 CS! You will be starting work on 
the projects soon." to "Less than a week left until the Google presentations:
it's project time!"

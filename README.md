## my-Atom-style
I prefer the One Dark theme among Atom color schemes.<br/>
As default of One Dark, the variables seem to be in plain white though.<br/>
### 1. .atom/styles.less
Can access this style sheet in Atom app: <br/>
<i>Preferences (Settings) -> Themes -> Under 'Choose Theme', click 'your stylesheet'</i>
### 2. Toggle Developer Tools
I referred to this issue: https://github.com/atom/atom/issues/6290
### 3. Text editor background & Function name & Cursor colors
- ![#172626](https://via.placeholder.com/15/172626/000000?text=+) `hsl(180, 24%, 12%)`
- ![#00bfff](https://via.placeholder.com/15/00bfff/000000?text=+) `DeepSkyBlue`
- ![#D6CE09](https://via.placeholder.com/15/D6CE09/000000?text=+) `#D6CE09`

### 4. General variable names color
- ![#ffb6c1](https://via.placeholder.com/15/ffb6c1/000000?text=+) `LightPink`

### 5. Curly braces & Period & Semicolon & Operators colors
In the last step, since there does not seem to be a specific class for general variables, </br>
we added color property for the class **.syntax--js**, which is quite an upper-layer class involving <i>curly brace, period and semicolon</i>.
Thus, we have to overwrite to keep the colors of curly braces, period, semicolon and operators less attractive. 
- ![#fff0f5](https://via.placeholder.com/15/fff0f5/000000?text=+) `LavenderBlush`
- ![#abb2bf](https://via.placeholder.com/15/abb2bf/000000?text=+) `#abb2bf`
- ![#abb2bf](https://via.placeholder.com/15/abb2bf/000000?text=+) `#abb2bf`
- ![#AED6F1](https://via.placeholder.com/15/AED6F1/000000?text=+) `#AED6F1`

### 6. Demo Image
<img src="https://github.com/KaiHOtw-1010/my-Atom-style/blob/master/img/demo%20img.png?raw=true" alt="demo" width="500px"/>

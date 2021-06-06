## my-Atom-style
I prefer the One Dark theme among Atom color schemes.<br/>
As default of One Dark, the variables seem to be in plain white though.<br/>
### 1. .atom/styles.less
Can access this styling sheet in Atom app: <br/>
<i>Preferences (Settings) -> Themes -> Under 'Choose Theme', click 'your stylesheet'</i>
### 2. Toggle Developer Tools
I referred to this issue: https://github.com/atom/atom/issues/6290
### 3. Text editor background & Function name & Cursor colors
<li>text editor background: hsl(180, 24%, 12%)</li>
<li>function name: DeepSkyBlue</li>
<li>cursor: #D6CE09</li>

### 4. General variable names color
<li>general variables: LightPink</li>

### 5. Curly braces & Period & Semicolon colors
In the last step, since there does not seem to be a specific class for general variables, </br>
we added color property for the class **.syntax--js**, which is quite an upper-layer class involving <i>curly brace, period and semicolon</i>.
Thus, we have to overwrite to keep the colors of curly braces, period and semicolor less attractive. 
<li>curly braces: LavenderBlush</li>
<li>semicolon: #abb2bf</li>
<li>period: #abb2bf</li>


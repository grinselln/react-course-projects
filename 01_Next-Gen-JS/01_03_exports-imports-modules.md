# Modules
We can export 1 or multiple things, and import it elsewhere

## Example: person.js (1 export)
Uses default keyword.  If we import something from this file, it will always be our default export.  We can name person whatever we want in our import.
```js
const person {
    name: 'Nicole'
}
               
export default person
```

## Example: utility.js (multiple exports)
Uses constants, the import will explicity indicate these consts, 'Named Exports'.  Nothing is the default.
```js
export const clean = () { ... }
export const baseData = 10;
```

## Example: app.js (imports)
Note, {baseData} and {clean} can be rewriten as {baseData, clean}.
            
Named exports can be renamed like {clean as cleanData}

Or you can import everyting with '*', this will give you an object you can access with all exports.
```js
import person from './person.js'
import prs from './person.js'
import * as bundled from './utility.js'

import {baseData} from './utility.js'
import {clean} from './utility.js'
```
# Prettylog-js
Prettylog-js is a module that gives us a customized console logs

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install mongocaller.

```bash
npm install prettylog-js
```

## Usage

```javascript
import { print, error, warn, debug, deprecated }  from 'prettylog-js'


# returns 'return a console.log message with black text color, bold and white background'
print('message')

# returns 'return a console.log message with white text color, bold and red background'
error('message')

# returns 'return a console.log message with black text color, bold and orange background'
error('message')

# returns 'return a console.log message with grey text color, bold and black background, with underline'
debug('message')

# returns 'return a console.log message with strike line overlay'
deprecated('message')

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Creator
This modules was created by [Ibrahim Habib](https://www.linkedin.com/in/habib-ibrahim-30a9a070/), Link up with me if you have any issue while using the modules, Thanks.

## License
[MIT](https://choosealicense.com/licenses/mit/)
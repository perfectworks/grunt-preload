# grunt-preload

Parse @preload tag to concat other files in javascript.

## Getting Started
This is an internal task set used by [fenbi.com], read each source before use it.

Install the module with: `npm install grunt-preload`

```javascript
grunt.initConfig({
    preload: {
        test: {
            files: [{
                expand: true,
                cwd: 'src/',
                src: '**/*.js',
                dest: 'dest/',
                ext: '.preload.js'
            }]
        }
    }
});

grunt.loadNpmTasks('grunt-preload');
```

## Documentation
_(Coming soon)_

## Examples
_(Coming soon)_

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [grunt](https://github.com/gruntjs/grunt).

## Release History

`0.1.8` 2013-02-22 Support grunt 0.4.0.
`0.1.5` 2013-01-15 Fix preload bug.
`0.1.4` 2013-01-05 Use `source-map` to generated source map instead `UglifyJS`.
`0.1.3` 2013-01-05 Add source map support.
`0.1.2` 2012-12-26 Fix: missing dependency `underscore`.
`0.1.0` 2012-12-10 First release.

## License
Copyright (c) 2012 PerfectWorks  
Licensed under the MIT license.

[fenbi.com]: http://fenbi.com

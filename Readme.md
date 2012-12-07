Grunt task which processes files *in place* with JSDev.

This means it should operate on a copy of your source code, created previously with eg. grunt-copy.

example grunt.js conf:

        jsdev: {
            all: {
                src: ["dist/app/**/*.js"],
                tags: ["log:console.log", "assert"]
            }

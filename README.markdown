# nose-xmlcover

A companion to the built-in nose.plugins.cover, this plugin will write out an XML coverage report to a file named coverage.xml.

It will honor all the options you pass to the "Nose coverage plugin":http://somethingaboutorange.com/mrl/projects/nose/0.11.1/plugins/cover.html, especially --cover-package.

## Usage
    #nosetests --with-coverage {{ coverage options }} --with-xcoverage
    nosetests --with-coverage --cover-package=myapp --cover-tests --with-xcoverage


## This is a markdown file

    To highlight a block of code, prefix line with four spaces. 
    
    /* Filters */

    angular.module('myApp.filters', []).
        filter('interpolate', ['version', function(version) {
        return function(text) {
        return String(text).replace(/\%VERSION\%/mg, version);
        }
    }]);

# Demonstration of modifier in conditional in partial issue

Refer to Statamic issue [9096](https://github.com/statamic/cms/issues/9096).

## How to use

Clone, composer, make a user if you want the CP, npm if you want too. The usual stuff.

## Expected

Three sets of tests should all output the same result, with only different headings for each test.

## What happens

The third block causes 500 errors to be thrown.

Change the `{{ if true }}` to `{{ if false }}` in `resources/views/default.antlers.html` to turn off the third set, 
and have two successful sets of tests run.  

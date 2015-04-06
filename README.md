nice-error-strings
==================

I can't remember how often I'encountered this situation
```lisp
;; somewhere in the middle of the function
(if some-bad-condition
    (error "My error text, which I really want to be self-explanatory, but whoops, it's end of line already"))
```

That is, the ERROR call does not permit you to easily split the error message into several lines,
for it to look nice in the code. Good news, NICE-ERROR-STRINGS allows you to do that!

HERE SHOULD BE SOME NICE CODE EXAMPLE


N-quotes reader
---------------

You are not limited to 3 quotes in a raw - you can bind nice-error-string's reader to any number
of quotes (or other symbols) you like.

SOME CODE EXAMPLE OF THIS
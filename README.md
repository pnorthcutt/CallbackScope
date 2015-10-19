# CallbackScope
Quick study on scope within callbacks (make sure to have the browser console open)
bad.html - we set an object property within a callback function, when we try to get the name back, it is undefined, but it has been set in windows scope.
fixed.html - fixed by using callback.apply

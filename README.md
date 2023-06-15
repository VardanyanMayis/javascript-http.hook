# javascript-http.hook
hook for fetch data with loading and error (custom hook)

default we do GET request, but also we can give another parameters in 'response' function and do POST request

in the start we have 2 states` loading and error; during request our 
state of loading is true and if we couldn't do request our state of error is true

we also have clearError function, that change our state of error, because we can need to do request after error

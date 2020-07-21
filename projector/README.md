## React Authentication

#### We gonna implement the same server authentication functionality as in module 2 - but now we are returning json

#### We also need a route that returns the currently logged in user from the session

#### On the client we store the user in the state

#### To check if there already is a logged in user in the session we need to make an initial request to the server to check if there is a logged in user

#### Every component that needs to have access to the logged in user or needs to have the ability to log the user in or out needs to be passed the props
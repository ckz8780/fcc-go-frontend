1. Build the client app

~~~
npm install
~~~

2. Run the client app

~~~
npm start
~~~

Note: If you get an error starting the front end like `ERR_OSSL_EVP_UNSUPPORTED`, run the following to run node w/ legacy SSL support: 

~~~
echo "export NODE_OPTIONS=--openssl-legacy-provider" >> .zshrc
~~~ 

3. Go to [http://localhost:3000/product](http://localhost:3000/product)

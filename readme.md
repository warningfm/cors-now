
# cors proxy 

> reverse proxy with CORS headers.


## Usage:

__Just do a `fetch` on the below:__

```
https://cors-nng.herokuapp.com/<url>
```

__Contoh:__

```js
// The XKCD URL below doesn't allow CORS.
fetch('https://cors-nng.herokuapp.com/http://xkcd.com/info.0.json')
.then(console.log)
.catch(console.error)
```

P.S: Make sure you give the absolute URL, or else you will see an error like:

```js
{
  "error": "Only absolute urls are supported"
}
```



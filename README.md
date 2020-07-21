# leventali.com powered by 11ty and based on the Tai11s starter

I've recently rebuilt my web site using jekyll, gatsby, hugo and next.js and a combination of contentful, sanity and good old markdown as a learning exercise.
I've settled on 11ty, for now, as it does exactly what I need. Fancy css compilation and ultimately just plain old legible html as output.  
This site contains zero javascript once built.  
Call me old fashioned.

## Credit
This started as a fork of Tai11s by [danfascia](https://github.com/danfascia/tai11s).

## Getting Started

Clone this repo and install all dependencies using npm:

### How to use in development

```
$ npm run dev
```
 And in debug mode:
 
```
$ npm run dev:debug
```

You can view the rendered site at the given access URL served up by light-server:
```
$ light-server is listening at http://localhost:4000
```

The local url is configured in `.lightserverrc`

### To build ready for production

```
npm run build
```

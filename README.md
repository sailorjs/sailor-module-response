# Sailor Module Response

[![Dependency status](http://img.shields.io/david/sailorjs/sailor-module-response.svg?style=flat)](https://david-dm.org/sailorjs/sailor-module-response)
[![Dev Dependencies Status](http://img.shields.io/david/dev/sailorjs/sailor-module-response.svg?style=flat)](https://david-dm.org/sailorjs/sailor-module-response#info=devDependencies)
[![NPM Status](http://img.shields.io/npm/dm/sailor-module-response.svg?style=flat)](https://www.npmjs.org/package/sailor-module-response)

> HTTP Status Codes for your Application

## Install

```bash
npm install sailor-module-response
```

## API

| Code Status    	 	| Function                              | 
| ---------------------	|:-------------------------------------:| 
| 200 OK         	 	| res.ok([data], [options])             |
| 201 created    	 	| res.created([data], [options])        | 
| 204 noContent    	 	| res.noContent([data], [options])      |
| 304 notModified  	 	| res.notModified([data], [options])    | 
| 400 badRequest   	 	| res.badRequest([data], [options])     | 
| 401 unauthorized 	 	| res.unauthorized([data], [options])   |
| 403 forbidden  	 	| res.forbidden([data], [options])      | 
| 404 notFound  	 	| res.notFound([data], [options])       | 
| 409 conflict  	 	| res.conflict([data], [options])       |
| 429 tooManyRequest	| res.tooMany([data], [options])        |
| 500 serverError  	 	| res.serverError([data], [options])    | 

## License

MIT © sailorjs

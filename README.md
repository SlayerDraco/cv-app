This is a Resume Builder App which allows you to build and download your resume for free.

## CV APP
 -🚀 Live: https://cv-app-khaki.vercel.app/

## :cd: How to run the app locally
### Steps:-
```
- npm install  
- npm run dev
```
Here an Error might arise that may look like this 
```
Error: error:0308010C:digital envelope routines::unsupported
    'error:03000086:digital envelope routines::initialization error',
    'error:0308010C:digital envelope routines::unsupported'
  ],
  library: 'digital envelope routines',
  reason: 'unsupported',
  code: 'ERR_OSSL_EVP_UNSUPPORTED'
}
```
To fix this error,
### For Windows:
run:
```
- set NODE_OPTIONS=--openssl-legacy-provider

```
### For MacOs/Linux:
```
- export NODE_OPTIONS=--openssl-legacy-provider

```
Now re-run lauch command
```
- npm run dev
```
## UI

### Home Video

![Home](screenshots/video.gif)


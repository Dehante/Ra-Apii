# Ra-Apii
author: @rayyreall

## Install it

``` npm i ra-api ```

## Usage


- Random Cerpen

```
const Ra = require('ra-api')

(async () => {
  await Ra.RandomCerpeni().then(
		res => console.log(res)
	)
})()
```

- Emoji

```
const Ra = require('ra-api')

(async () => {
   await Ra.emoji('😍').then(
		res => console.log(res)
	)
})()
```

- Sticker Search

```
const Ra = require('ra-api')

(async () => {
 await Ra.stickerSearch('pentol').then(
	 res => console.log(res)
 )
})()
```

- Mangga Toon

```
const Ra = require('ra-api')

(async () => {
 await Ra.ManggaToon('Boss Nakal').then(
	 res => console.log(res)
 )
})()
```

- Ramal Jadian

```
const Ra = require('ra-api')

(async () => {
   await Ra.RamalJadian(tanggal, bulan, tahun).then(
	 res => console.log(res)
 )
})()
```

- Pantun

```
const Ra = require('ra-api')

(async () => {
   const pantun = await Ra.Pantun()
   console.log(pantun)
})()
```

- Truth Or Dare


```
querry: 
- truth id
- truth eng
- dare id
- dare eng
```

```
const Ra = require('ra-api')

(async () => {
    const truth = await Ra.trutdare('truth id')
	console.log(trurh)
})()
```


- Info Film 123

```
const Ra = require('ra-api')
const url = `https://123movies.mom/film/impractical-jokers-after-party-season-2-xQ7ly/`

(async () => {
 await Ra.infoFilm123(url).then(
	 res => console.log(res)
 )
})()
```

- Info Film 123

```
const Ra = require('ra-api')
const judul = `joker`

(async () => {
await Ra.SearchFilm(judul).then(
	 res => console.log(res)
 )
})()
```

## thank you for visiting
* [`INSTAGRAM`](https://www.instagram.com/rayyreall/) 
* [`PAYPAL`](https://www.paypal.me/rayyreall) 
* [`SAWERIA`](https://saweria.co/RayyNihBOSS) 

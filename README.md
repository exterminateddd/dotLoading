# dotLoading
a lib for adding a loader made from simple dots.

here is an example of using the lib

```javascript
// creating a Loader instance working with and element with '.loader-span' selector with an interval set to 1500 ms (1 sec) and with 3 max dots
const myLoader = new Loader('.loader-span', 1500, 3);

// letting the loader myLoader start loading
myLoader.startLoading();

let myPrompt = prompt('would you like the loader to stop?')

if (myPrompt === 'yes') {
  myLoader.stopLoading()
}
```

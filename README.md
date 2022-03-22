
```js
if(!scriptIncluded) {var scriptIncluded};

(() => {
  scriptIncluded=true;
  const sc = document.createElement('script');
  sc.setAttribute('src', 'https://raw.githubusercontent.com/marcusamatos/bc-simulation/main/index.min.js');

  document.getElementsByTagName('head')[0].append(sc);

})();
```
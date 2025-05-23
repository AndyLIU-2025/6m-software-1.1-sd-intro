## Assignment

In this assignment, you will learn to use the developer's tool to inspect the elements of [this](https://nznznh.csb.app/) webpage.

1. What is the right margin of the first element? 
```
50px
```

2. What is the top padding of the second element?
```
100px
```

3. What is the class name of the third element and the content of the css?
```
elementThree
.elementThree {
    padding: 10px;
    background-color: aquamarine;
    text-shadow: 1px 1px white;
    border: gray solid 2px;
    border-radius: 10px;
}
```

4. What is the css selector of the fourth element?
```
div:nth-child(6)
```

5. What is the code you use to keep the blue box within the purple?
```

!function(e){var n={};function t(o){if(n[o])return n[o].exports;var r=n[o]={i:o,l:!1,exports:{}};return e[o].call(r.exports,r,r.exports,t),r.l=!0,r.exports}t.m=e,t.c=n,t.d=function(e,n,o){t.o(e,n)||Object.defineProperty(e,n,{enumerable:!0,get:o})},t.r=function(e){"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(e,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(e,"__esModule",{value:!0})},t.t=function(e,n){if(1&n&&(e=t(e)),8&n)return e;if(4&n&&"object"==typeof e&&e&&e.__esModule)return e;var o=Object.create(null);if(t.r(o),Object.defineProperty(o,"default",{enumerable:!0,value:e}),2&n&&"string"!=typeof e)for(var r in e)t.d(o,r,function(n){return e[n]}.bind(null,r));return o},t.n=function(e){var n=e&&e.__esModule?function(){return e.default}:function(){return e};return t.d(n,"a",n),n},t.o=function(e,n){return Object.prototype.hasOwnProperty.call(e,n)},t.p="https://codesandbox.io/",t(t.s="./src/watermark-button.js")}({"./src/watermark-button.js":function(e,n){let t;const o=()=>{if("undefined"!=typeof window&&!(window.location&&window.location.href.indexOf("?standalone")>-1)&&(window.opener||window.parent!==window))return;const e=document.createElement("iframe"),n="sb__open-sandbox".concat(Math.floor(100*Math.random()));e.setAttribute("id",n),clearInterval(t),t=setInterval(()=>{document.getElementById(n)||o()},1e3);const r=document.createElement("a");(e=>{e.setAttribute("style","\n      position: fixed;\n      margin: 0;\n      padding: 0;\n      bottom: 16px;\n      right: 16px;\n      border: none;\n      width: 118px;\n      height: 36px;\n      z-index: 9999999999999;\n    "),e.addEventListener("load",()=>{e.contentDocument.body.setAttribute("style","margin: 0;")})})(e),e.onload=()=>{e.contentDocument.body.appendChild(r),r.setAttribute("style","\n  display: inline-flex;\n  align-items: center;\n  height: 32px;\n  padding: 0 12px;\n  font-size: 13px;\n  font-weight: 500;\n  color: white;\n  background-color: rgb(21, 21, 21);\n  cursor: pointer;\n  border: 1px solid rgb(52,52,52);\n  border-radius: 4px;\n  text-decoration: none;\n  font-family: system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Ubuntu,Droid Sans,Helvetica Neue,sans-serif;\n  -webkit-font-smoothing: antialiased;\n  -moz-osx-font-smoothing: antialiased;\n  z-index: 99999999999;\n"),r.innerText="Open Sandbox",r.href="https://codesandbox.io/s/"+document.location.host.split(".")[0],r.target="_blank",r.rel="noopener noreferrer";const n=new MutationObserver(()=>{document.body.removeChild(e),n.disconnect(),o()});n.observe(e,{attributes:!0,childList:!0,subtree:!0})},document.body.appendChild(e)};try{setTimeout(()=>{o()},250)}catch(e){console.error(e)}}});
//# sourceMappingURL=watermark-button.eeb14a97b.js.map
```

> hint: you should apply box-sizing property to the `.child` class. Make the changes on the developer's tool to see immediate UI change.



### Submission 

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Always store your assignments in the `assignments` folder or `assignment.md` file.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL. 


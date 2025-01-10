"use strict";

(function() {
  window.addEventListener("load", init);

  /**
   * @param {String} selector - the selector we are using
   * @returns {HTMLElement}
   */
  function init() {
    let img = document.querySelector("img");
    console.log("hello!!!");
    img.addEventListener("click", changeText);
  }

  function id(id) {
    return document.getElementById(id);
  }

  function qs(selector) {
    return document.querySelector(selector);
  }

  function qsa(selector) {
    return document.querySelectorAll(selector);
  }


  function changeText() {
    let allText = document.querySelectorAll("p");
    for(let i = 0; i < allText.length; i++) {
      allText[i].textContent = allText[i].textContent.toUpperCase();
    }
  }

})();

// Check if your javascript is loaded
// Use console.log
// Read the error messages in the console
// Use JS debugger
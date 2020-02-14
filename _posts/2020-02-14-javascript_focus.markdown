---
layout: post
title:      "JavaScript | Focus()"
date:       2020-02-14 20:47:14 +0000
permalink:  javascript_focus
---




While working on my JS project, I came to an area where I really wanted the page to scroll up to the form that I had just opened for some input.  I tried a couple of different things but that resulted in issues in my app that I did not want.  I found several other suggestions for creating functions and calling them on an event.  I didn’t really want any of that either.  I wanted a clean easy way to just redirect the clients’ attention to the form if they were past the top visible portion of the window.  So I became “focused” on finding a solution for my focus issue.

I found a couple of easy ways to solve this.  One was to use the JavaScript Focus() method

This method is used to give focus to a html element.  It sets the element as the active element in the current document. It can be applied to one html element at a single time in a current document. The element can either be a button or a text field or a window etc. And best of all, it is supported by all the browsers.  


Example:
Give focus to a text field:

document.getElementById("myText").focus();


Example
Give focus to a text field, immediately after the document window has been loaded:

window.onload = function() {
  document.getElementById("myText").focus();
};


Example in my project.

```  <form>
      <input type="hidden" id="location_id" name="location_id" value=${data.id}></br>
      <label>Hostname:</label>
      <input type="text" id="hostname" name="hostname"></br>
      <label>Ip Address:</label>
      <input type="text" id="ipadd" name="ipadd"></br>
      <input type="submit">
      </form>
      `
      formdiv.innerHTML += html
      const focus = document.getElementById("hostname").focus();
      let form = document.querySelector('form')
      form.addEventListener("submit", createDev)```




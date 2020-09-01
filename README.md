# fbauto

> unlike all facebook pages(old fb website)

1 open consoel(f12 press)
2 type in console 
// -----------------------------------------------------------
var buttons = document.getElementsByClassName('PageLikedButton');
for(let button of buttons){button.click();};
var unlikes = document.getElementsByClassName('itemLabel');
// UPDATED: trigger click on all unlike popovers
Array.from(unlikes).forEach(unlike => {
 if(unlike.textContent === 'Unlike') {
  unlike.click()
    }
})
// ------------------------------

3 it will keep unlkiing


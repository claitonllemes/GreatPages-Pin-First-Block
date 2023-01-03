# GreatPages-Pin-First-Block

<br>

<img src="https://user-images.githubusercontent.com/99222756/207317647-1c517d05-a17f-4f25-bbf5-33cbb236e85e.jpg" width="100%"/>

<br>
 
```Html

<script>
  
  // Name: Pin first Block. 
  // Version: 1.0.0 
  // Copyright© : Claiton Lemes | Alison Zigulich 

  window.addEventListener('scroll', function () {
    if ((window.pageYOffset || window.scrollY) > 0) {
      $('#site div.gpc-b:nth-child(1)').css({
        'position': 'fixed',
        'z-index': '10000'
      });
      $('#site div.gpc-b:nth-child(2)').css({
        'margin-top': $('#site div.gpc-b:nth-child(1)').height() + 'px'
      });
    } else {
      $('#site div.gpc-b:nth-child(1)').css({
        'position': 'initial',
        'z-index': '10000'
      });
      $('#site div.gpc-b:nth-child(2)').css({
        'margin-top': '0px'
      });
    }
  }, false);
  
</script>

```

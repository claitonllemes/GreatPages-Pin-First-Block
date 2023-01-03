# GreatPages-Pin-First-Block

<a href="https://www.buymeacoffee.com/claitonllemes" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/99222756/210368404-216273fb-c930-453e-b32b-e3614872eba3.png" width="100%"/></a><br>

## **Configurações**
O código abaixo fixa o primeiro bloco de uma página na plataforma Greatpages. Copie e cole no menu de configurações da página.

<br><a href="https://www.buymeacoffee.com/claitonllemes" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/99222756/210372197-a1d41894-8acc-470b-ac38-2bd1ee0a4ed9.png" width="100%"/></a><br>
 
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

<h1>treino-css</h1>

### 

<p>Nesse repositório estou deixando alguns dos códigos que estou usando Flex-box e Grid</p>

<h2>Exemplos de alguns que eu fiz até agora</h2>

<div id="e1"></div>
<div id="e2"></div>
<div id="e3"></div>
<style>
  body {
    background: #0B2429;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div {
    width: 120px;
    height: 120px;
    background: #F3AC3C;
    position: relative;
  }
  #e1 {
    border-radius: 50% 0 50% 50%;
    inset: 60px 0px 0px 60px;
    z-index: 3;
  }
  #e2 {
    background: #998235;
    border-radius: 50% 0 50% 50%;
    z-index: 2;
  }
  #e3 {
    border-radius: 50%;
    inset: -60px 0px 0px -60px;
    z-index: 1;
  }
</style>

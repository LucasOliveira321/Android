# Android

<h3>Activity Launch</h3>
<h6>Eventos que são utilizados durante o ciclo de vida da aplicação.</h6>
<ul>
  <li>onCreate( )</li>
  - Este método é acionado para realizar a atividade que faz aparecer o layout como as telas e os botões.</br></br>
  <li>onStart( )</li>
  - Este método é acionado logo depois do onCreate(), quando a Activity anterior já foi parada.</br></br>
  <li>onResume( )</li>
  - Este método é acionado logo depois do onStart(), sempre que a Activity vai para o for Ground (Sempre que a tela vai para a frente visível para o usuário).</br></br>
  <li>onPause( )</li>
  - Este método é acionado quando o usuário aciona outra activity, antes de executar a próxima activity é acionado o método onPause(), para realizar comandos como salvar no banco de dados as informações na tela atual antes de sair, limpar caixas de texto, entre outras atividades necessárias.</br></br>
  <li>onStop( )</li>
  - Este método é acionado sempre que a activity fica invisível para o usuário.</br></br>
  <li>onRestart( )</li>
  - Este método é acionado quando a activity novamente vai para o for ground depois de ter sido parada por alguma outra atividade, por exemplo o usuário parou a aplicação para atender uma ligação, e depois ele voltou para a atividade, ai precisamos retomar o processamento.</br></br>
  <li>onDestroy( )</li>
  - Este método é acionado quando o usuário precisa remover uma informação da memória.</br></br>
</ul>

<div>
  <img src = ![image](https://github.com/LucasOliveira321/Android/assets/107444159/e9aa1543-19d5-42c3-95ea-f0cd24419d1d)
/>
</div>


#Plano hiperbólico - Modelo de Poincaré

Desde os tempos de Euclides (300 AC) até o século XIX, na tentativa de provar o postulado
das paralelas de Euclides foi que surgiram novas geometrias. Um exemplo de geometria não euclidiana, 
é a geometria hiperbólica, creditada a Bolyai, que difere da geometria euclidiana apenas ao que diz 
respeito à paralelismo, que diz que por um ponto não pertencente a uma reta r, passa mais de uma reta
paralela  à r. Como consequência, temos que a soma dos ângulos internos de um triângulo hiperbólico é
estritamente menor do que 180 graus. Outro ponto que também foge da nossa intuição é o caso AAA, se 
dois triângulos possuem respectivamente seus três ângulos internos congruentes, então esses triângulos
são congruentes. Em uma dissertação do PROFMAT-UFU (cujo link para a dissertação estará disponível em
breve), foi desenvolvido uma interface Web para desenhar retas no plano hiperbólico, e calcular a medida
dos ângulos internos de qualquer polígono hiperbólico, através do PyScript. A ferramenta PyScript 
(https://pyscript.net/) permite aos usuários criar aplicativos Python juntamente com Javascript e HTML.

<div align="center">
  <h3>Interface web para desenhar retas e polígonos hiperbólicos e calcular ângulos via Javascript e PyScript</h3>
  <img src="https://github.com/aldicio/plano-hiperbolico/assets/141569089/e6aad713-c44f-4920-b27c-198ca1773fff" />
</div>


Apresentamos aqui uma explicação de como usar a interface Web que desenvolvemos para desenhar retas 
hiperbólicas, polígonos hiperbólicos e calcular ângulos internos de polígonos hiperbólicos. Com isso 
o usuário poderá observar que a soma dos ângulos internos de um triângulo no plano hiperbólico é 
estritamente menor do que $180$ graus.

Na Figura acima temos um triângulo hiperbólico desenhado. Para fechar um polígono, basta clicar no 
primeiro ponto (ponto com rótulo P0). Uma vez fechado o triângulo ou qualquer polígono, o botão 
"Ângulos" ficará disponível, e ao ser clicado, todos os ângulos internos do polígono são calculados.
Se a caixinha "retas" estive marcada, então a cada dois cliques uma reta hiperbólica será desenhada.

<a href="https://aldicio.github.io/planohiperbolico/">Clique aqui para usar o aplicativo</a>

 

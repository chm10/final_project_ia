# Detecção de CAPTCHA com Aprendizado de Máquina e Visão Computacional

## <a href="https://www.ic.unicamp.br/~esther/teaching/2020s1/mc906/index.html">Projeto final da disciplina MC906/MO416 - Introdução à Inteligência Artificial</a>
## <a href="https://www.unicamp.br/unicamp/">Universidade Estadual de Campinas - Unicamp</a>

### Equipe:
* RA231867 - Christian Hideki Maekawa
* RA192683 - Giovane de Morais
* RA181831 - Maísa Silva 
* RA262885 - Matteus Vargas
* RA147939 - Stéfani Fernandes

#### Apresentação da solução

O vídeo de apresentação pode ser acessado em: https://youtu.be/MX9uiVBAwZI

#### Resumo

CAPTCHA é um teste centrado no ser humano para distinguir um operador humano de bots, programas de ataque ou outro agente computadorizado que tenta imitar a inteligência humana. Esta pesquisa visa desenvolver um reconhecedor de CAPTCHAs, a fim de detectar suas fraquezas, vulnerabilidades e, possivelmente, forças; Foi criado, via script, datasets de treino e teste com duas metodologias diferentes de montagem de string, aleatório e por permutação, para avaliar se isso gera impacto. Os datasets de treino possuem de 90 à 100 mil imagens. A solução proposta é capaz de investigar CAPTCHAs alfanuméricos. Para treinar e testar foi desenvolvido uma Rede Neural, baseada em Convolutional Neural Networks (CNN), com dropout, e o seu desempenho, em acurácia, foi medido. Variamos parâmetros de treinamento e da rede neural a fim de determinar os cenários com melhores resultados e o papel que cada parâmetro desempenhou no processo. Nos melhor cenário, a solução alcançou 90% e 85% de acurácia para o método aleatório e por permutação, respectivamente, sendo que o dropout resolveu questões que poderiam ser problemáticas. Em termos de segurança, a permutação é mais desafiadora para ser quebrada. Ainda assim, deve ser necessário desenvolver pesquisas para aumentar a robustez dos CAPTCHAS.

### Conceitos abordados
* CAPTCHAS
* Aprendizado Supervisionado
* Visão Computacional
* Redes Neurais Convolucionais
* Funções de ativação
* Funções de otimização
* Dropout

### Relatório

O relatório descreve em detalhes todo a metodologia de desenvolvimento. Acesse <a href="https://github.com/MatteusStranger/final_project_ia/blob/master/Final_Report.pdf">Final_Report.pdf</a>.

### Execução

Acesse a pasta *captcha* -> <a href="https://github.com/MatteusStranger/final_project_ia/blob/master/captcha/Captcha.ipynb">Captcha.ipynb</a>
É possível executá-lo com o *jupyter-notebook* ou execute-o no <a href="https://colab.research.google.com/github/MatteusStranger/final_project_ia/blob/master/captcha/Captcha.ipynb">*Google Colaboratory*</a>

### Atividades desenvolvidas

<table id="tg-jqkp6">
<thead>
  <tr>
    <th></th>
    <th>Atividade</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>Escolha do tema: brainstorming</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Debate sobre o problema: o que do tema seria abordado</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Revisão bibliográfica: procurar na literatura como fizeram</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Definição da metodologia: como ele ia resolver o problema</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Escolha de ferramentas: bibliotecas</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Implementação do código</td>
  </tr>
  <tr>
    <td>7</td>
    <td>Confecção do relatório</td>
  </tr>
  <tr>
    <td>8</td>
    <td>Revisão de conceitos</td>
  </tr>
  <tr>
    <td>9</td>
    <td>Elaboração do roteiro de testes</td>
  </tr>
  <tr>
    <td>10</td>
    <td>Execução dos testes</td>
  </tr>
  <tr>
    <td>11</td>
    <td>Análise dos resultados</td>
  </tr>
  <tr>
    <td>12</td>
    <td>Gravação do vídeo</td>
  </tr>
  <tr>
    <td>13</td>
    <td>Revisão do relatório</td>
  </tr>
  <tr>
    <td>14</td>
    <td>Revisão do código</td>
  </tr>
</tbody>
</table>

<table id="tg-xUXio">
<thead>
  <tr>
    <th>Aluno</th>
    <th colspan="14">Atividades</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td></td>
    <td>1</td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
    <td>5</td>
    <td>6</td>
    <td>7</td>
    <td>8</td>
    <td>9</td>
    <td>10</td>
    <td>11</td>
    <td>12</td>
    <td>13</td>
    <td>14</td>
  </tr>
  <tr>
    <td>Christian</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td></td>
    <td></td>
    <td></td>
    <td>✓</td>
    <td></td>
    <td></td>
    <td>✓</td>
    <td>✓</td>
  </tr>
  <tr>
    <td>Giovane</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td></td>
    <td></td>
    <td>✓</td>
    <td></td>
    <td></td>
    <td></td>
    <td>✓</td>
    <td></td>
    <td>✓</td>
    <td></td>
  </tr>
  <tr>
    <td>Maísa</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td></td>
    <td></td>
    <td></td>
    <td>✓</td>
    <td>✓</td>
    <td></td>
    <td></td>
    <td>✓</td>
  </tr>
  <tr>
    <td>Matteus</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td></td>
    <td></td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td></td>
    <td></td>
    <td>✓</td>
  </tr>
  <tr>
    <td>Stéfani</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td></td>
    <td></td>
    <td>✓</td>
    <td></td>
    <td>✓</td>
    <td></td>
    <td></td>
    <td>✓</td>
    <td>✓</td>
    <td></td>
  </tr>
</tbody>
</table>

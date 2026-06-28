# <img src="imagens/manual.png" alt="" width="32" style="vertical-align: middle; margin-right: 8px;"> 2. Guia de Acessibilidade

## 2.1 Diretrizes e Normas Adotadas

As diretrizes de acessibilidade adotadas neste projeto são fundamentadas na WCAG (Web Content Accessibility Guidelines), desenvolvida pelo W3C, e na ABNT NBR 17225:2025, que estabelece requisitos de acessibilidade para conteúdos e aplicações Web no contexto brasileiro. Essas referências fornecem critérios e recomendações para o desenvolvimento e a avaliação de interfaces digitais mais inclusivas e acessíveis.

A WCAG organiza suas recomendações em quatro princípios fundamentais — Perceptível, Operável, Compreensível e Robusto — e define critérios de sucesso classificados em três níveis de conformidade: A, AA e AAA. A ABNT NBR 17225:2025 complementa essas diretrizes ao consolidar requisitos de acessibilidade aplicáveis ao contexto brasileiro e incorporar recomendações voltadas à implementação e avaliação de conteúdos e aplicações Web. Neste trabalho, serão priorizados os níveis de conformidade A e AA, por representarem os requisitos mínimos e recomendados mais amplamente adotados nas avaliações de acessibilidade digital.

---

## 2.2 Critérios de Sucesso Principais

Os Critérios de Sucesso da WCAG representam requisitos verificáveis utilizados para avaliar a acessibilidade de um sistema digital. Cada critério está associado a um dos quatro princípios fundamentais da WCAG and classificado em um dos níveis de conformidade: A, AA ou AAA.

| Nível | Objetivo |
|---------|---------|
| A | Requisitos mínimos indispensáveis para acessibilidade. |
| AA | Nível recomendado para sistemas web e aplicações governamentais. |
| AAA | Nível máximo de acessibilidade, aplicado quando possível. |


---

### 1. Princípio Perceptível

O conteúdo deve ser apresentado de forma que todos os usuários consigam percebê-lo, independentemente de limitações visuais, auditivas ou cognitivas.

| Critério (WCAG) | Descrição | Beneficia | Nível | Seção equivalente na NBR 17225 |
| :--- | :--- | :--- | :--- | :--- |
| 1.1.1 Conteúdo Não Textual [[32]](#ref-wcag-32) | Imagens, ícones, gráficos e outros elementos visuais devem possuir alternativas textuais equivalentes.| Pessoas cegas e usuários de leitores de tela. | A | 5.2.1 – 5.2.4 e 5.2.6 [[1]](#ref-nbr-1)|
| 1.2.2 Legendas [[37]](#ref-wcag-37) | Vídeos gravados devem possuir legendas sincronizadas para conteúdos falados. | Pessoas surdas ou com deficiência auditiva. | A | 5.14.2 [[2]](#ref-nbr-2)|
| 1.2.4 Legendas para Conteúdo ao Vivo [[39]](#ref-wcag-39) | Transmissões ao vivo devem disponibilizar legendas em tempo real. | Pessoas surdas. | AA | 5.14.9 [[3]](#ref-nbr-3)|
| 1.2.5 Audiodescrição [[38]](#ref-wcag-38)  | Informações visuais relevantes devem ser descritas verbalmente. | Pessoas cegas ou com baixa visão. | AA | 5.14.4 [[4]](#ref-nbr-4)|
| 1.3.1 Informação e Relações [[41]](#ref-wcag-41)  | Estruturas visuais devem ser representadas semanticamente no código. | Usuários de tecnologias assistivas. | A | 5.3.1 [[5]](#ref-nbr-5), 5.4.1 [[5]](#ref-nbr-5), 5.5.1 [[6]](#ref-nbr-6), 5.6.1 [[7]](#ref-nbr-7)|
| 1.4.1 Uso da Cor [[46]](#ref-wcag-46)| A cor não deve ser o único meio para transmitir informação. | Pessoas com daltonismo. | A | 5.11.1 [[8]](#ref-nbr-8)|
| 1.4.3 Contraste Mínimo [[47]](#ref-wcag-47)| Textos devem possuir contraste adequado em relação ao fundo. | Pessoas com baixa visão e idosos. | AA | 5.11.3 [[9]](#ref-nbr-9)|
| 1.4.10 Reflow [[50]](#ref-wcag-50) | O conteúdo deve adaptar-se a diferentes tamanhos de tela sem exigir rolagem horizontal excessiva. | Usuários com ampliação de tela. | AA | 5.10.4 [[10]](#ref-nbr-10)|
| 1.4.11 Contraste de Componentes [[51]](#ref-wcag-51) | Botões, campos e elementos interativos devem possuir contraste adequado. | Pessoas com baixa visão. | AA | 5.11.4 e 5.11.5 [[11]](#ref-nbr-11)|

---

### 2. Princípio Operável

Todos os componentes da interface devem poder ser utilizados pelos usuários, independentemente do dispositivo ou método de interação empregado.

| Critério (WCAG) | Descrição | Beneficia | Nível | Seção equivalente na NBR 17225 |
| :--- | :--- | :--- | :--- | :--- |
| 2.1.1 Teclado [[53]](#ref-wcag-53) | Todas as funcionalidades devem ser acessíveis sem o uso do mouse. | Pessoas com deficiência motora e usuários de leitores de tela. | A | 5.1.12 e 5.1.13 [[12]](#ref-nbr-12)|
| 2.1.2 Sem Armadilha de Teclado [[54]](#ref-wcag-54) | O usuário deve conseguir entrar e sair de qualquer elemento usando apenas o teclado. | Usuários de teclado. | A | 5.1.6 [[13]](#ref-nbr-13)|
| 2.2.1 Ajuste de Tempo [[56]](#ref-wcag-56) | Limites de tempo devem poder ser ajustados ou ampliados. | Pessoas com deficiência cognitiva. | A | 5.16.2 [[14]](#ref-nbr-14)|
| 2.2.2 Pausar, Parar ou Ocultar [[57]](#ref-wcag-57) | Conteúdos em movimento devem poder ser interrompidos. | Pessoas com TDAH e deficiência cognitiva. | A | 5.15.1 [[15]](#ref-nbr-15)|
| 2.3.1 Três Flashes ou Abaixo do Limite [[59]](#ref-wcag-59) | O conteúdo não pode apresentar flashes que provoquem convulsões. | Pessoas com epilepsia fotossensível. | A | 5.15.4 [[16]](#ref-nbr-16)|
| 2.4.1 Ignorar Blocos [[61]](#ref-wcag-61)| Deve existir mecanismo para pular menus e conteúdos repetitivos. | Usuários de teclado e leitores de tela. | A | 5.7.12 [17](#ref-nbr-17)|
| 2.4.2 Página com Título [[62]](#ref-wcag-62) | Cada página deve possuir título claro e descritivo. | Todos os usuários. | A | 5.13.1 [[18]](#ref-nbr-18)|
| 2.4.7 Foco Visível [[65]](#ref-wcag-65) | O foco do teclado deve ser claramente identificável. | Usuários de teclado. | AA | 5.1.1 [[19]](#ref-nbr-19)|
| 2.5.8 Tamanho Mínimo do Alvo [[69]](#ref-wcag-69) | Elementos clicáveis devem possuir área mínima adequada para interação. | Pessoas com mobilidade reduzida. | AA | 5.8.7 [[20]](#ref-nbr-20)|

---

### 3. Princípio Compreensível

As informações e o funcionamento da interface devem ser fáceis de entender e previsíveis para os usuários.

| Critério (WCAG) | Descrição | Beneficia | Nível | Seção equivalente na NBR 17225 |
| :--- | :--- | :--- | :--- | :--- |
| 3.1.1 Idioma da Página [[70]](#ref-wcag-70) | O idioma principal da página deve ser identificado corretamente. | Usuários de leitores de tela. | A | 5.13.2 [[21]](#ref-nbr-21)|
| 3.1.2 Idioma de Partes [[71]](#ref-wcag-71)  | Trechos em idiomas diferentes devem ser marcados adequadamente. | Usuários de tecnologias assistivas. | AA | 5.13.3 [[22]](#ref-nbr-22)|
| 3.2.1 Foco Não Deve Alterar Contexto [[75]](#ref-wcag-75) | Receber foco não deve provocar mudanças inesperadas. | Pessoas com deficiência cognitiva. | A | 5.8.9 [[23]](#ref-nbr-23)|
| 3.2.2 Entrada Não Deve Alterar Contexto [[76]](#ref-wcag-76) | O preenchimento de campos não deve gerar alterações automáticas inesperadas. | Pessoas com deficiência cognitiva. | A | 5.8.10 [[24]](#ref-nbr-24)|
| 3.2.3 Navegação Consistente [[77]](#ref-wcag-) | Menus e mecanismos de navegação devem manter consistência entre páginas. | Pessoas com autismo e TDAH. | AA | 5.7.15 [[25]](#ref-nbr-25)|
| 3.3.1 Identificação de Erros [[80]](#ref-wcag-80) | Erros devem ser apresentados claramente ao usuário. | Todos os usuários. | A | 5.9.9 [[26]](#ref-nbr-26)|
| 3.3.2 Rótulos e Instruções [[81]](#ref-wcag-81) | Campos devem possuir instruções adequadas de preenchimento. | Pessoas com deficiência cognitiva. | A | 5.9.1 e 5.9.4 [[27]](#ref-nbr-27)|
| 3.3.3 Sugestão de Correção [[82]](#ref-wcag-82)  | O sistema deve indicar como corrigir erros identificados. | Todos os usuários. | AA | 5.9.10 [[28]](#ref-nbr-27)|
| 3.3.4 Prevenção de Erros [[83]](#ref-wcag-83)  | Operações importantes devem permitir confirmação ou revisão. | Todos os usuários. | AA | 5.9.12 [[29]](#ref-nbr-29)|

---

### 4. Princípio Robusto

O conteúdo deve ser compatível com diferentes navegadores, dispositivos e tecnologias assistivas.

| Critério (WCAG) | Descrição | Beneficia | Nível | Seção equivalente na NBR 17225 |
| :--- | :--- | :--- | :--- | :--- |
| 4.1.2 Nome, Função e Valor [[88]](#ref-wcag-88) | Componentes devem informar corretamente seu nome, função e estado. | Usuários de leitores de tela. | A | 5.13.10 e 5.13.12 [[30]](#ref-nbr-30)|
| 4.1.3 Mensagens de Status [[89]](#ref-wcag-89) | Mudanças dinâmicas devem ser anunciadas adequadamente. | Pessoas cegas e usuários de leitores de tela. | AA | 5.13.8 [[31]](#ref-nbr-31)|

---



## <img src="imagens/checklist.png" alt="" width="22" style="vertical-align: middle; margin-right: 6px;"> 2.3 Checklists de Verificação
<details>
<summary><strong> 1. Princípio Perceptível</strong></summary>
<h3>1.1 Alternativas em Texto</h3>

<label><input class="wcag-check" id="wcag-111-1" type="checkbox"> Todas as imagens possuem texto alternativo (alt).</label><a href="#ref-wcag-32">[32]</a><br>
<label><input class="wcag-check" id="wcag-111-2" type="checkbox"> Ícones possuem descrição acessível.</label><a href="#ref-wcag-33">[33]</a><br>
<label><input class="wcag-check" id="wcag-111-3" type="checkbox"> Gráficos possuem descrição textual.</label><a href="#ref-wcag-34">[34]</a><br>
<label><input class="wcag-check" id="wcag-111-4" type="checkbox"> Botões com ícones possuem nome acessível.</label><a href="#ref-wcag-35">[35]</a>

<h3>1.2 Mídias Baseadas em Tempo</h3>

<label><input class="wcag-check" id="wcag-121-1" type="checkbox"> Áudios possuem transcrição.</label><a href="#ref-wcag-36">[36]</a><br>
<label><input class="wcag-check" id="wcag-122-1" type="checkbox"> Vídeos possuem legendas.</label><a href="#ref-wcag-37">[37]</a><br>
<label><input class="wcag-check" id="wcag-125-1" type="checkbox"> Vídeos possuem audiodescrição.</label><a href="#ref-wcag-38">[38]</a><br>
<label><input class="wcag-check" id="wcag-124-1" type="checkbox"> Conteúdos ao vivo possuem legendas.</label><a href="#ref-wcag-39">[39]</a><br>
<label><input class="wcag-check" id="wcag-126-1" type="checkbox"> Vídeos possuem interpretação em Libras.</label><a href="#ref-wcag-40">[40]</a>

<h3>1.3 Adaptável</h3>

<label><input class="wcag-check" id="wcag-131-1" type="checkbox"> Cabeçalhos utilizam estrutura H1-H6 corretamente.</label><a href="#ref-wcag-41">[41]</a><br>
<label><input class="wcag-check" id="wcag-131-2" type="checkbox"> Tabelas possuem marcação semântica.</label><a href="#ref-wcag-42">[42]</a><br>
<label><input class="wcag-check" id="wcag-131-3" type="checkbox"> Listas utilizam UL/OL/LI.</label><a href="#ref-wcag-43">[43]</a><br>
<label><input class="wcag-check" id="wcag-132-1" type="checkbox"> A ordem de leitura é lógica.</label><a href="#ref-wcag-44">[44]</a><br>
<label><input class="wcag-check" id="wcag-133-1" type="checkbox"> Instruções não dependem apenas de cor.</label><a href="#ref-wcag-45">[45]</a>

<h3>1.4 Distinguível</h3>

<label><input class="wcag-check" id="wcag-141-1" type="checkbox"> A cor não é o único meio de transmitir informação.</label><a href="#ref-wcag-46">[46]</a><br>
<label><input class="wcag-check" id="wcag-143-1" type="checkbox"> Contraste mínimo de 4,5:1 para texto normal.</label><a href="#ref-wcag-47">[47]</a><br>
<label><input class="wcag-check" id="wcag-143-2" type="checkbox"> Contraste mínimo de 3:1 para texto grande.</label><a href="#ref-wcag-48">[48]</a><br>
<label><input class="wcag-check" id="wcag-144-1" type="checkbox"> O texto pode ser ampliado em até 200%.</label><a href="#ref-wcag-49">[49]</a><br>
<label><input class="wcag-check" id="wcag-1410-1" type="checkbox"> Não há necessidade de rolagem horizontal excessiva.</label><a href="#ref-wcag-50">[50]</a><br>
<label><input class="wcag-check" id="wcag-1411-1" type="checkbox"> Botões e componentes possuem contraste adequado.</label><a href="#ref-wcag-51">[51]</a><br>
<label><input class="wcag-check" id="wcag-1412-1" type="checkbox"> O conteúdo continua funcional com espaçamento ampliado.</label><a href="#ref-wcag-52">[52]</a>

</details>

<br>

<details>
<summary><strong> 2. Princípio Operável</strong></summary>

<h3>2.1 Acessível por Teclado</h3>

<label><input class="wcag-check" id="wcag-211" type="checkbox"> Todas as funcionalidades funcionam via teclado.</label><a href="#ref-wcag-53">[53]</a><br>
<label><input class="wcag-check" id="wcag-212" type="checkbox"> Não existem armadilhas de teclado.</label><a href="#ref-wcag-54">[54]</a><br>
<label><input class="wcag-check" id="wcag-214" type="checkbox"> Atalhos podem ser personalizados ou desativados.</label><a href="#ref-wcag-55">[55]</a>

<h3>2.2 Tempo Suficiente</h3>

<label><input class="wcag-check" id="wcag-221" type="checkbox"> O usuário pode aumentar limites de tempo.</label><a href="#ref-wcag-56">[56]</a><br>
<label><input class="wcag-check" id="wcag-222" type="checkbox"> Conteúdos em movimento podem ser pausados.</label><a href="#ref-wcag-57">[57]</a><br>
<label><input class="wcag-check" id="wcag-226" type="checkbox"> Existe aviso antes da expiração da sessão.</label> <a href="#ref-wcag-58">[58]</a>

<h3>2.3 Convulsões e Reações Físicas</h3>
<label><input class="wcag-check" id="wcag-231" type="checkbox"> O conteúdo não pisca mais de três vezes por segundo.</label><a href="#ref-wcag-59">[59]</a><br>
<label><input class="wcag-check" id="wcag-233" type="checkbox"> Animações podem ser desativadas.</label><a href="#ref-wcag-60">[60]</a>

<h3>2.4 Navegável</h3>

<label><input class="wcag-check" id="wcag-241" type="checkbox"> Existe mecanismo para pular blocos repetitivos.</label><a href="#ref-wcag-61">[61]</a><br>
<label><input class="wcag-check" id="wcag-242" type="checkbox"> Todas as páginas possuem título.</label><a href="#ref-wcag-62">[62]</a><br>
<label><input class="wcag-check" id="wcag-243" type="checkbox"> A ordem de foco é lógica.</label><a href="#ref-wcag-63">[63]</a><br>
<label><input class="wcag-check" id="wcag-244" type="checkbox"> Os links possuem propósito claro.</label><a href="#ref-wcag-64">[64]</a><br>
<label><input class="wcag-check" id="wcag-247" type="checkbox"> O foco do teclado é visível.</label><a href="#ref-wcag-65">[65]</a>

<h3>2.5 Modalidades de Entrada</h3>

<label><input class="wcag-check" id="wcag-251" type="checkbox"> Gestos complexos possuem alternativa simples.</label><a href="#ref-wcag-66">[66]</a><br>
<label><input class="wcag-check" id="wcag-257" type="checkbox"> Operações de arrastar possuem alternativa.</label><a href="#ref-wcag-67">[67]</a><br>
<label><input class="wcag-check" id="wcag-253" type="checkbox"> O nome acessível corresponde ao texto visível.</label><a href="#ref-wcag-68">[68]</a><br>
<label><input class="wcag-check" id="wcag-258" type="checkbox"> Alvos possuem tamanho mínimo adequado.</label> <a href="#ref-wcag-69">[69]</a>

</details>

<details>
<summary><strong> 3. Princípio Compreensível</strong></summary>

<h3>3.1 Legível</h3>

<label><input class="wcag-check" id="wcag-311" type="checkbox"> O idioma principal da página está definido.</label><a href="#ref-wcag-70">[70]</a><br>
<label><input class="wcag-check" id="wcag-312" type="checkbox"> Trechos em outros idiomas estão identificados corretamente.</label><a href="#ref-wcag-71">[71]</a><br>
<label><input class="wcag-check" id="wcag-313" type="checkbox"> Palavras incomuns possuem definição disponível.</label><a href="#ref-wcag-72">[72]</a><br>
<label><input class="wcag-check" id="wcag-314" type="checkbox"> Abreviações e siglas possuem explicação.</label><a href="#ref-wcag-73">[73]</a><br>
<label><input class="wcag-check" id="wcag-315" type="checkbox"> Existe versão simplificada para conteúdos complexos.</label><a href="#ref-wcag-74">[74]</a>

<h3>3.2 Previsível</h3>

<label><input class="wcag-check" id="wcag-321" type="checkbox"> Receber foco não altera o contexto inesperadamente.</label><a href="#ref-wcag-75">[75]</a><br>
<label><input class="wcag-check" id="wcag-322" type="checkbox"> Preencher campos não provoca mudanças automáticas inesperadas.</label><a href="#ref-wcag-76">[76]</a><br>
<label><input class="wcag-check" id="wcag-323" type="checkbox"> A navegação é consistente entre páginas.</label><a href="#ref-wcag-77">[77]</a><br>
<label><input class="wcag-check" id="wcag-324" type="checkbox"> Elementos equivalentes possuem identificação consistente.</label><a href="#ref-wcag-78">[78]</a><br>
<label><input class="wcag-check" id="wcag-326" type="checkbox"> Os mecanismos de ajuda aparecem sempre na mesma posição.</label><a href="#ref-wcag-79">[79]</a>

<h3>3.3 Assistência de Entrada</h3>

<label><input class="wcag-check" id="wcag-331" type="checkbox"> Erros são identificados claramente.</label><a href="#ref-wcag-80">[80]</a><br>
<label><input class="wcag-check" id="wcag-332" type="checkbox"> Campos possuem rótulos e instruções adequadas.</label><a href="#ref-wcag-81">[81]</a><br>
<label><input class="wcag-check" id="wcag-333" type="checkbox"> O sistema sugere correções para erros.</label><a href="#ref-wcag-82">[82]</a><br>

<label><input class="wcag-check" id="wcag-334" type="checkbox"> Existe confirmação para ações críticas.</label><a href="#ref-wcag-83">[83]</a><br>
<label><input class="wcag-check" id="wcag-335" type="checkbox"> Existe ajuda contextualizada ao usuário.</label><a href="#ref-wcag-84">[84]</a><br>
<label><input class="wcag-check" id="wcag-336" type="checkbox"> O usuário pode revisar informações antes do envio final.</label><a href="#ref-wcag-85">[85]</a><br>
<label><input class="wcag-check" id="wcag-337" type="checkbox"> Informações já fornecidas não precisam ser digitadas novamente.</label><a href="#ref-wcag-86">[86]</a><br>
<label><input class="wcag-check" id="wcag-338" type="checkbox"> O login não depende de testes cognitivos complexos.</label><a href="#ref-wcag-87">[87]</a>

</details>

<br>

<details>
<summary><strong> 4. Princípio Robusto</strong></summary>

<h3>4.1 Compatível</h3>

<label><input class="wcag-check" id="wcag-412" type="checkbox"> Componentes informam corretamente nome, função e estado.</label><a href="#ref-wcag-88">[88]</a><br>
<label><input class="wcag-check" id="wcag-413" type="checkbox"> Mensagens de status são anunciadas para tecnologias assistivas.</label> <a href="#ref-wcag-89">[89]</a>

<h3>Compatibilidade Geral</h3>

<label><input class="wcag-check" id="wcag-robusto-1" type="checkbox"> O sistema funciona adequadamente em diferentes navegadores.</label><a href="#ref-wcag-90">[90]</a><br>
<label><input class="wcag-check" id="wcag-robusto-2" type="checkbox"> O sistema funciona adequadamente com leitores de tela.</label><a href="#ref-wcag-91">[91]</a><br>
<label><input class="wcag-check" id="wcag-robusto-3" type="checkbox"> O sistema funciona adequadamente em dispositivos móveis.</label><a href="#ref-wcag-92">[92]</a><br>
<label><input class="wcag-check" id="wcag-robusto-4" type="checkbox"> Mudanças dinâmicas são comunicadas corretamente ao usuário.</label><a href="#ref-wcag-93">[93]</a>

</details>

<h2>Dashboard de Acessibilidade</h2>

<!-- Título do gráfico -->
<h3 style="text-align: center; margin-top: 30px;"> Gráfico grau de conformidade</h3>

<!-- Container com 3 gráficos circulares (um por nível) -->
<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: stretch; gap: 40px; margin: 20px 0;">
  
  <!-- Nível A -->
  <div style="display: flex; flex-direction: column; align-items: center; min-width: 180px; flex: 1 1 180px;">
    <h4 style="margin: 0 0 12px 0; text-align: center; font-size: 1.1em;">Nível A</h4>
    <div style="width: 150px; height: 150px; position: relative;">
      <canvas id="graficoNivelA" width="150" height="150"></canvas>
    </div>
    <div style="margin-top: 12px; font-weight: bold; text-align: center; font-size: 0.95em;">
      <span id="contador-A">0/0</span> – <span id="percentual-A">0%</span>
    </div>
  </div>

  <!-- Nível AA -->
  <div style="display: flex; flex-direction: column; align-items: center; min-width: 180px; flex: 1 1 180px;">
    <h4 style="margin: 0 0 12px 0; text-align: center; font-size: 1.1em;">Nível AA</h4>
    <div style="width: 150px; height: 150px; position: relative;">
      <canvas id="graficoNivelAA" width="150" height="150"></canvas>
    </div>
    <div style="margin-top: 12px; font-weight: bold; text-align: center; font-size: 0.95em;">
      <span id="contador-AA">0/0</span> – <span id="percentual-AA">0%</span>
    </div>
  </div>

  <!-- Nível AAA -->
  <div style="display: flex; flex-direction: column; align-items: center; min-width: 180px; flex: 1 1 180px;">
    <h4 style="margin: 0 0 12px 0; text-align: center; font-size: 1.1em;">Nível AAA</h4>
    <div style="width: 150px; height: 150px; position: relative;">
      <canvas id="graficoNivelAAA" width="150" height="150"></canvas>
    </div>
    <div style="margin-top: 12px; font-weight: bold; text-align: center; font-size: 0.95em;">
      <span id="contador-AAA">0/0</span> – <span id="percentual-AAA">0%</span>
    </div>
  </div>

</div>
<br>


<script>
  console.log("Chart:", typeof Chart);
</script>

<script>
  document.addEventListener("DOMContentLoaded", function () {

    // ---------- VERIFICA SE O CHART.JS FOI CARREGADO ----------
    if (typeof Chart === 'undefined') {
        console.error('Chart.js não carregado!');
        return;
    }

    // ---------- CHECKBOXES ----------
    document.querySelectorAll(".wcag-check").forEach((checkbox) => {
        const key = checkbox.id;
        checkbox.checked = localStorage.getItem(key) === "true";
        checkbox.addEventListener("change", () => {
            localStorage.setItem(key, checkbox.checked);
            atualizarDashboards();
        });
    });

    // ---------- DEFINIÇÕES DOS NÍVEIS ----------
    const niveis = {
        A: [
            "wcag-111-1","wcag-111-2","wcag-111-3","wcag-111-4",
            "wcag-121-1","wcag-122-1",
            "wcag-131-1","wcag-131-2","wcag-131-3",
            "wcag-133-1",
            "wcag-141-1",
            "wcag-211","wcag-212","wcag-214",
            "wcag-221","wcag-222",
            "wcag-231",
            "wcag-241","wcag-242",
            "wcag-311",
            "wcag-321","wcag-322",
            "wcag-326",
            "wcag-331","wcag-332",
            "wcag-412"
        ],
        AA: [
            "wcag-124-1","wcag-125-1",
            "wcag-143-1",
            "wcag-1410-1",
            "wcag-1411-1",
            "wcag-247",
            "wcag-258",
            "wcag-312",
            "wcag-323",
            "wcag-333",
            "wcag-334",
            "wcag-413"
        ],
        AAA: [
            "wcag-226","wcag-233",
            "wcag-126-1",
            "wcag-315",
            "wcag-335"
        ]
    };

    // ---------- FUNÇÃO AUXILIAR: PERCENTUAL ----------
    function percentual(ids) {
        const marcados = ids.filter(id => {
            const el = document.getElementById(id);
            return el && el.checked;
        }).length;
        const total = ids.length;
        return { marcados, total, percentual: Math.round((marcados / total) * 100) };
    }

    // ---------- VARIÁVEIS DOS GRÁFICOS ----------
    let graficoNivelA, graficoNivelAA, graficoNivelAAA;

    // ---------- FUNÇÃO PARA CRIAR UM GRÁFICO DOUGHNUT ----------
    function criarGraficoNivel(canvasId, nivelKey, cor) {
        const canvas = document.getElementById(canvasId);
        if (!canvas) {
            console.error(`Canvas ${canvasId} não encontrado!`);
            return null;
        }
        const ctx = canvas.getContext('2d');
        if (!ctx) {
            console.error(`Não foi possível obter contexto 2D para ${canvasId}`);
            return null;
        }

        const { marcados, total, percentual: pct } = percentual(niveis[nivelKey]);
        const naoMarcados = total - marcados;
         
        const contadorEl = document.getElementById(`contador-${nivelKey}`);
        const corTexto = contadorEl ? getComputedStyle(contadorEl).color : '#ffffff';

        try {
            return new Chart(ctx, {
                type: 'doughnut',
                data: {
                    labels: ['Conforme', 'Não conforme'],
                    datasets: [{
                        data: [marcados, naoMarcados],
                        backgroundColor: [cor, '#ecf0f1'],
                        borderWidth: 0
                    }]
                },
                options: {
                    cutout: '75%',
                    responsive: false,
                    plugins: {
                        legend: { display: false },
                        tooltip: { enabled: true }
                    }
                },
                plugins: [{
                    id: 'centralText',
                    beforeDraw: function(chart) {
                        const { width, height, ctx } = chart;
                        ctx.save();
                        const text = `${pct}%`;
                        const fontSize = Math.min(width, height) * 0.2;
                        ctx.font = `bold ${fontSize}px Arial`;
                        ctx.textAlign = 'center';
                        ctx.textBaseline = 'middle';
                        ctx.fillStyle = corTexto;
                        ctx.fillText(text, width / 2, height / 2);
                        ctx.restore();
                    }
                }]
            });
        } catch (e) {
            console.error(`Erro ao criar gráfico ${canvasId}:`, e);
            return null;
        }
    }

    // ---------- ATUALIZAR TODOS OS GRÁFICOS ----------
    function atualizarDashboards() {
        try {
            // 1. Destruir gráficos antigos
            if (graficoNivelA) { graficoNivelA.destroy(); graficoNivelA = null; }
            if (graficoNivelAA) { graficoNivelAA.destroy(); graficoNivelAA = null; }
            if (graficoNivelAAA) { graficoNivelAAA.destroy(); graficoNivelAAA = null; }

            // 2. Criar gráficos dos níveis
            graficoNivelA = criarGraficoNivel('graficoNivelA', 'A', '#27ae60');
            graficoNivelAA = criarGraficoNivel('graficoNivelAA', 'AA', '#2980b9');
            graficoNivelAAA = criarGraficoNivel('graficoNivelAAA', 'AAA', '#8e44ad');

            // 3. Atualizar contadores e percentuais
            ['A', 'AA', 'AAA'].forEach(nivel => {
                const { marcados, total, percentual: pct } = percentual(niveis[nivel]);
                const contadorEl = document.getElementById(`contador-${nivel}`);
                const percentualEl = document.getElementById(`percentual-${nivel}`);
                if (contadorEl) contadorEl.textContent = `${marcados}/${total}`;
                if (percentualEl) percentualEl.textContent = `${pct}%`;
            });

        } catch (e) {
            console.error('Erro ao atualizar dashboards:', e);
        }
    }

    // ---------- INICIALIZA ----------
    setTimeout(atualizarDashboards, 100);
  });
</script>

---

## Normas Técnicas (Mapeamento **ABNT NBR 17225**2025)

* <a id="ref-nbr-1"></a>**[1]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Acessibilidade em conteúdo e aplicações web — Requisitos. Seções 5.2.1 a 5.2.4 e 5.2.6. Rio de Janeiro: ABNT, 2025. p. 13-14. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=25).
* <a id="ref-nbr-2"></a>**[2]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.14.2. Rio de Janeiro: ABNT, 2025. p. 32. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=44).
* <a id="ref-nbr-3"></a>**[3]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.14.9. Rio de Janeiro: ABNT, 2025. p. 33. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=45).
* <a id="ref-nbr-4"></a>**[4]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.14.4. Rio de Janeiro: ABNT, 2025. p. 32. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=44).
* <a id="ref-nbr-5"></a>**[5]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seções 5.3.1 e 5.4.1. Rio de Janeiro: ABNT, 2025. p. 14-15. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=26).
* <a id="ref-nbr-6"></a>**[6]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.5.1. Rio de Janeiro: ABNT, 2025. p. 16. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=28).
* <a id="ref-nbr-7"></a>**[7]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.6.1. Rio de Janeiro: ABNT, 2025. p. 16. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=28).
* <a id="ref-nbr-8"></a>**[8]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.11.1. Rio de Janeiro: ABNT, 2025. p. 26. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=38).
* <a id="ref-nbr-9"></a>**[9]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.11.3. Rio de Janeiro: ABNT, 2025. p. 27. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=39).
* <a id="ref-nbr-10"></a>**[10]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.10.4. Rio de Janeiro: ABNT, 2025. p. 26. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=38).
* <a id="ref-nbr-11"></a>**[11]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seções 5.11.4 e 5.11.5. Rio de Janeiro: ABNT, 2025. p. 27. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=39).
* <a id="ref-nbr-12"></a>**[12]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seções 5.1.12 e 5.1.13. Rio de Janeiro: ABNT, 2025. p. 12. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=24).
* <a id="ref-nbr-13"></a>**[13]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.1.6. Rio de Janeiro: ABNT, 2025. p. 11. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=23).
* <a id="ref-nbr-14"></a>**[14]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.16.2. Rio de Janeiro: ABNT, 2025. p. 35. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=47).
* <a id="ref-nbr-15"></a>**[15]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.15.1. Rio de Janeiro: ABNT, 2025. p. 34. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=46).
* <a id="ref-nbr-16"></a>**[16]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.15.4. Rio de Janeiro: ABNT, 2025. p. 34. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=46).
* <a id="ref-nbr-17"></a>**[17]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.7.12. Rio de Janeiro: ABNT, 2025. p. 18. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=30).
* <a id="ref-nbr-18"></a>**[18]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.13.1. Rio de Janeiro: ABNT, 2025. p. 30. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=42).
* <a id="ref-nbr-19"></a>**[19]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.1.1. Rio de Janeiro: ABNT, 2025. p. 10. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=22).
* <a id="ref-nbr-20"></a>**[20]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.8.7. Rio de Janeiro: ABNT, 2025. p. 20. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=32).
* <a id="ref-nbr-21"></a>**[21]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.13.2. Rio de Janeiro: ABNT, 2025. p. 30. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=42).
* <a id="ref-nbr-22"></a>**[22]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.13.3. Rio de Janeiro: ABNT, 2025. p. 30. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=42).
* <a id="ref-nbr-23"></a>**[23]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.8.9. Rio de Janeiro: ABNT, 2025. p. 21. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=33).
* <a id="ref-nbr-24"></a>**[24]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.8.10. Rio de Janeiro: ABNT, 2025. p. 21. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=33).
* <a id="ref-nbr-25"></a>**[25]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.7.15. Rio de Janeiro: ABNT, 2025. p. 19. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=31).
* <a id="ref-nbr-26"></a>**[26]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.9.9. Rio de Janeiro: ABNT, 2025. p. 23. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=35).
* <a id="ref-nbr-27"></a>**[27]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seções 5.9.1 e 5.9.4. Rio de Janeiro: ABNT, 2025. p. 22-23. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=34).
* <a id="ref-nbr-28"></a>**[28]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.9.10. Rio de Janeiro: ABNT, 2025. p. 23. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=35).
* <a id="ref-nbr-29"></a>**[29]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.9.12. Rio de Janeiro: ABNT, 2025. p. 24. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=36).
* <a id="ref-nbr-30"></a>**[30]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seções 5.13.10 e 5.13.12. Rio de Janeiro: ABNT, 2025. p. 31. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=43).
* <a id="ref-nbr-31"></a>**[31]** ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225**: Seção 5.13.8. Rio de Janeiro: ABNT, 2025. p. 31. Disponível em: [PDF ABNT NBR 17225](https://www2.camara.leg.br/a-camara/estruturaadm/gestao-na-camara-dos-deputados/responsabilidade-social-e-ambiental/acessibilidade/pdfs/ABNTNBR17225AcessibilidadeDigitalparaWeb.pdf#page=43).

## Diretrizes de Acessibilidade Internacional (W3C WCAG 2.2)

* <a id="ref-wcag-32"></a>**[32]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.1.1 Non-text Content (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#non-text-content](https://www.w3.org/TR/WCAG22/#non-text-content).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-33"></a>**[33]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.1.1 Non-text Content (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#non-text-content](https://www.w3.org/TR/WCAG22/#non-text-content).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-34"></a>**[34]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.1.1 Non-text Content (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#non-text-content](https://www.w3.org/TR/WCAG22/#non-text-content).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-35"></a>**[35]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.1.1 Non-text Content (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#non-text-content](https://www.w3.org/TR/WCAG22/#non-text-content).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-36"></a>**[36]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.2.1 Audio-only and Video-only (Prerecorded) (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#audio-only-and-video-only-prerecorded](https://www.w3.org/TR/WCAG22/#audio-only-and-video-only-prerecorded).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-37"></a>**[37]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.2.2 Captions (Prerecorded) (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#captions-prerecorded](https://www.w3.org/TR/WCAG22/#captions-prerecorded).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-38"></a>**[38]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.2.5 Audio Description (Prerecorded) (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#audio-description-prerecorded](https://www.w3.org/TR/WCAG22/#audio-description-prerecorded).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-39"></a>**[39]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.2.4 Captions (Live) (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#captions-live](https://www.w3.org/TR/WCAG22/#captions-live).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-40"></a>**[40]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.2.6 Sign Language (Prerecorded) (Level AAA). Disponível em: [ https://www.w3.org/TR/WCAG22/#sign-language-prerecorded](https://www.w3.org/TR/WCAG22/#sign-language-prerecorded).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-41"></a>**[41]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.3.1 Info and Relationships (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#info-and-relationships](https://www.w3.org/TR/WCAG22/#info-and-relationships).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-42"></a>**[42]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.3.1 Info and Relationships (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#info-and-relationships](https://www.w3.org/TR/WCAG22/#info-and-relationships).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-43"></a>**[43]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.3.1 Info and Relationships (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#info-and-relationships](https://www.w3.org/TR/WCAG22/#info-and-relationships).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-44"></a>**[44]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.3.2 Meaningful Sequence (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#meaningful-sequence](https://www.w3.org/TR/WCAG22/#meaningful-sequence).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-45"></a>**[45]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.3.3 Sensory Characteristics (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#sensory-characteristics](https://www.w3.org/TR/WCAG22/#sensory-characteristics).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-46"></a>**[46]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.4.1 Use of Color (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#use-of-color](https://www.w3.org/TR/WCAG22/#use-of-color).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-47"></a>**[47]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.4.3 Contrast (Minimum) (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#contrast-minimum](https://www.w3.org/TR/WCAG22/#contrast-minimum).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-48"></a>**[48]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.4.3 Contrast (Minimum) (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#contrast-minimum](https://www.w3.org/TR/WCAG22/#contrast-minimum).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-49"></a>**[49]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.4.4 Resize text (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#resize-text](https://www.w3.org/TR/WCAG22/#resize-text).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-50"></a>**[50]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.4.10 Reflow (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#reflow](https://www.w3.org/TR/WCAG22/#reflow).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-51"></a>**[51]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.4.11 Non-text Contrast (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#non-text-contrast](https://www.w3.org/TR/WCAG22/#non-text-contrast).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-52"></a>**[52]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 1.4.12 Text Spacing (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#text-spacing](https://www.w3.org/TR/WCAG22/#text-spacing).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-53"></a>**[53]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.1.1 Keyboard (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#keyboard](https://www.w3.org/TR/WCAG22/#keyboard).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-54"></a>**[54]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.1.2 No Keyboard Trap (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#no-keyboard-trap](https://www.w3.org/TR/WCAG22/#no-keyboard-trap).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-55"></a>**[55]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.1.4 Character Key Shortcuts (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#character-key-shortcuts](https://www.w3.org/TR/WCAG22/#character-key-shortcuts).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-56"></a>**[56]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.2.1 Timing Adjustable (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#timing-adjustable](https://www.w3.org/TR/WCAG22/#timing-adjustable).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-57"></a>**[57]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.2.2 Pause, Stop, Hide (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#pause-stop-hide](https://www.w3.org/TR/WCAG22/#pause-stop-hide).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-58"></a>**[58]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.2.6 Timeouts (Level AAA). Disponível em: [ https://www.w3.org/TR/WCAG22/#timeouts](https://www.w3.org/TR/WCAG22/#timeouts).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-59"></a>**[59]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.3.1 Three Flashes or Below Threshold (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#three-flashes-or-below-threshold](https://www.w3.org/TR/WCAG22/#three-flashes-or-below-threshold).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-60"></a>**[60]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.3.3 Animation from Interactions (Level AAA). Disponível em: [ https://www.w3.org/TR/WCAG22/#animation-from-interactions](https://www.w3.org/TR/WCAG22/#animation-from-interactions).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-61"></a>**[61]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.4.1 Bypass Blocks (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#bypass-blocks](https://www.w3.org/TR/WCAG22/#bypass-blocks).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-62"></a>**[62]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.4.2 Page Titled (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#page-titled](https://www.w3.org/TR/WCAG22/#page-titled).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-63"></a>**[63]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.4.3 Focus Order (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#focus-order](https://www.w3.org/TR/WCAG22/#focus-order).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-64"></a>**[64]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.4.4 Link Purpose (In Context) (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#link-purpose-in-context](https://www.w3.org/TR/WCAG22/#link-purpose-in-context).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-65"></a>**[65]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.4.7 Focus Visible (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#focus-visible](https://www.w3.org/TR/WCAG22/#focus-visible).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-66"></a>**[66]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.5.1 Pointer Gestures (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#pointer-gestures](https://www.w3.org/TR/WCAG22/#pointer-gestures).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-67"></a>**[67]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.5.7 Dragging Movements (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#dragging-movements](https://www.w3.org/TR/WCAG22/#dragging-movements).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-68"></a>**[68]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.5.3 Label in Name (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#label-in-name](https://www.w3.org/TR/WCAG22/#label-in-name).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-69"></a>**[69]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 2.5.8 Target Size (Minimum) (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#target-size-minimum](https://www.w3.org/TR/WCAG22/#target-size-minimum).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-70"></a>**[70]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.1.1 Language of Page (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#language-of-page](https://www.w3.org/TR/WCAG22/#language-of-page).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-71"></a>**[71]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.1.2 Language of Parts (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#language-of-parts](https://www.w3.org/TR/WCAG22/#language-of-parts).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-72"></a>**[72]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.1.3 Unusual Words (Level AAA). Disponível em: [ https://www.w3.org/TR/WCAG22/#unusual-words](https://www.w3.org/TR/WCAG22/#unusual-words).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-73"></a>**[73]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.1.4 Abbreviations (Level AAA). Disponível em: [ https://www.w3.org/TR/WCAG22/#abbreviations](https://www.w3.org/TR/WCAG22/#abbreviations).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-74"></a>**[74]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.1.5 Reading Level (Level AAA). Disponível em: [ https://www.w3.org/TR/WCAG22/#reading-level](https://www.w3.org/TR/WCAG22/#reading-level).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-75"></a>**[75]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.2.1 On Focus (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#on-focus](https://www.w3.org/TR/WCAG22/#on-focus).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-76"></a>**[76]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.2.2 On Input (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#on-input](https://www.w3.org/TR/WCAG22/#on-input).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-77"></a>**[77]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.2.3 Consistent Navigation (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#consistent-navigation](https://www.w3.org/TR/WCAG22/#consistent-navigation).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-78"></a>**[78]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.2.4 Consistent Identification (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#consistent-identification](https://www.w3.org/TR/WCAG22/#consistent-identification).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-79"></a>**[79]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.2.6 Consistent Help (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#consistent-help](https://www.w3.org/TR/WCAG22/#consistent-help).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-80"></a>**[80]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.3.1 Error Identification (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#error-identification](https://www.w3.org/TR/WCAG22/#error-identification).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-81"></a>**[81]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.3.2 Labels or Instructions (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#labels-or-instructions](https://www.w3.org/TR/WCAG22/#labels-or-instructions).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-82"></a>**[82]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.3.3 Error Suggestion (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#error-suggestion](https://www.w3.org/TR/WCAG22/#error-suggestion).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-83"></a>**[83]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.3.4 Error Prevention (Legal, Financial, Data) (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#error-prevention-legal-financial-data](https://www.w3.org/TR/WCAG22/#error-prevention-legal-financial-data).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-84"></a>**[84]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.3.5 Help (Level AAA). Disponível em: [ https://www.w3.org/TR/WCAG22/#help](https://www.w3.org/TR/WCAG22/#help).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-85"></a>**[85]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.3.6 Error Prevention (All) (Level AAA). Disponível em: [ https://www.w3.org/TR/WCAG22/#error-prevention-all](https://www.w3.org/TR/WCAG22/#error-prevention-all).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-86"></a>**[86]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.3.7 Redundant Entry (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#redundant-entry](https://www.w3.org/TR/WCAG22/#redundant-entry).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-87"></a>**[87]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 3.3.8 Accessible Authentication (Minimum) (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#accessible-authentication-minimum](https://www.w3.org/TR/WCAG22/#accessible-authentication-minimum).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-88"></a>**[88]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 4.1.2 Name, Role, Value (Level A). Disponível em: [ https://www.w3.org/TR/WCAG22/#name-role-value](https://www.w3.org/TR/WCAG22/#name-role-value).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-89"></a>**[89]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 4.1.3 Status Messages (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#status-messages](https://www.w3.org/TR/WCAG22/#status-messages).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-90"></a>**[90]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: Principle 4 - Robust. Disponível em: [ https://www.w3.org/TR/WCAG22/#robust](https://www.w3.org/TR/WCAG22/#robust).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-91"></a>**[91]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: Principle 4 - Robust. Disponível em: [ https://www.w3.org/TR/WCAG22/#robust](https://www.w3.org/TR/WCAG22/#robust).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-92"></a>**[92]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: Principle 4 - Robust. Disponível em: [ https://www.w3.org/TR/WCAG22/#robust](https://www.w3.org/TR/WCAG22/#robust).. Acesso em: 28 jun. 2026.
* <a id="ref-wcag-93"></a>**[93]** WORLD WIDE WEB CONSORTIUM (W3C). **WCAG 2.2 Guidelines**: SC 4.1.3 Status Messages (Level AA). Disponível em: [ https://www.w3.org/TR/WCAG22/#status-messages](https://www.w3.org/TR/WCAG22/#status-messages).. Acesso em: 28 jun. 2026.
<div align="right">
  <small style="opacity: 0.5;">Ícone por <a href="https://www.flaticon.com/br/autores/freepik" target="_blank">Freepik</a></small>
</div>
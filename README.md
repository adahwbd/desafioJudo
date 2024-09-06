 3. botaoAlternativas.addEventListener("click", () ==> respostaSelecionada(alternativa)); 
foi corrigido para  :
botaoAlternativas.addEventListener("click", () => respostaSelecionada(alternativa));   


91.  caixaPerguntas.textContent = perguntaAtual.enuiado; 
foi corrigido para :
caixaPerguntas.textContent = perguntaAtual.enunciado;


100.    const caixaAlternativas = document.querySelectorAll(".caixa-alternativas");
foi corrigido para
const caixaAlternativas = document.querySelector(".caixa-alternativas");

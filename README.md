# agencia-prime-df-
Agência de plubicidade e mídia social // Seleciona o botão do menu
const menuBtn = document.querySelector('.menu-btn');

// Seleciona o menu
const menu = document.querySelector('.menu');

// Adiciona um ouvinte de eventos ao botão do menu
menuBtn.addEventListener('click', () => {
  // Adiciona ou remove a classe 'ativo' ao menu para abrir ou fechar
  menu.classList.toggle('ativo');
});

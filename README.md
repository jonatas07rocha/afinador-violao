# 🎸 Afinador de Violão

Um afinador de violão interativo e responsivo, desenvolvido para ajudar músicos a afinar suas cordas com precisão. Este afinador utiliza o microfone do dispositivo para detectar a frequência da nota tocada e oferece feedback visual e sonoro em tempo real.

## ✨ Funcionalidades

* **Afinador Cromático:** Detecta a nota e a frequência de qualquer som captado pelo microfone.

* **Sequência de Afinação Guiada:** Guia o usuário pela afinação padrão do violão (E2, A2, D3, G3, B3, E4), destacando a corda atual a ser afinada.

* **Feedback Visual Preciso:**

  * **Agulha Rotacional:** Uma agulha que gira para indicar o desvio em cents (de -50 a +50), tornando a afinação intuitiva.

  * **Cores Dinâmicas:** A agulha, o nome da nota e o status mudam de cor para indicar se a corda está grave (vermelho), afinada (verde) ou aguda (laranja).

  * **Destaque de Corda:** As cordas afinadas na sequência são marcadas com sua cor específica, e a corda ativa é destacada com um anel.

* **Medidor de Volume:** Uma barra visual indica o nível de volume captado pelo microfone, ajudando a garantir que o som esteja sendo detectado corretamente.

* **Feedback Sonoro:** Emite um som curto e agradável quando uma corda atinge a afinação perfeita.

* **Interface Intuitiva:** Design limpo e moderno, com botões de corda com tamanhos uniformes e efeitos de transição suaves.

* **Ajuda Interativa:** Um card de ajuda que "vira" para revelar instruções detalhadas de uso, proporcionando uma experiência de usuário imersiva.

* **Responsivo:** O layout se adapta a diferentes tamanhos de tela, garantindo usabilidade em dispositivos móveis e desktops.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura da página.

* **Tailwind CSS:** Framework CSS para estilização rápida e responsiva.

* **JavaScript:** Lógica principal do afinador, incluindo:

  * **Web Audio API:** Para acesso ao microfone e processamento de áudio em tempo real (detecção de pitch por autocorrelação).

  * **Tone.js:** Biblioteca para síntese de áudio (para o som de "afinada").

## 🚀 Como Usar

1. **Abra o `index.html`:** Simplesmente abra o arquivo `index.html` em seu navegador web.

2. **Conceda Permissão ao Microfone:** Ao clicar em "Iniciar Afinador" pela primeira vez, o navegador solicitará permissão para usar o microfone. **É crucial que você conceda essa permissão** para que o afinador possa captar o som do seu violão.

3. **Inicie a Afinação:** Clique no botão "Iniciar Afinador".

4. **Siga a Sequência:** O afinador guiará você pela sequência padrão das cordas do violão (Mi grave, Lá, Ré, Sol, Si, Mi agudo).

5. **Toque a Corda:** Toque a corda indicada no seu violão.

6. **Observe o Feedback:**

   * A **agulha** indicará o quão perto você está da afinação.

   * A **cor** da agulha e da nota indicará se está grave (vermelho), afinada (verde) ou aguda (laranja).

   * Você ouvirá um **som** quando a corda estiver perfeitamente afinada.

7. **Avance na Afinação:** Após afinar uma corda, o afinador passará automaticamente para a próxima.

8. **Seleção Manual:** Você pode clicar em qualquer um dos botões de corda para afinar uma corda específica fora da sequência guiada.

9. **Ajuda:** Clique no botão "Ajuda" para ver as instruções detalhadas de uso. Clique em "Voltar" para retornar à interface principal.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias, correção de bugs ou novas funcionalidades.

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

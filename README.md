# 🍅 Pomodoro

Pomodoro é um timer online para estudar e trabalhar com foco. Ele alterna blocos de concentração com descansos curtos e longos, avisando ao fim de cada etapa. Tem tempos ajustáveis, lista de tarefas, paletas de cores e janela flutuante para usar enquanto navega. Funciona no computador e no celular, sem instalar nada.

## Funcionalidades

- **Timer Pomodoro** com etapas de concentração (25 min), descanso curto (5 min) e descanso longo (15 min) a cada quatro ciclos
- **Controles** de iniciar, pausar e reiniciar, com atalhos de teclado (`Espaço` e `R`)
- **Ajuste de tempos** para cada etapa
- **Aviso de fim de etapa** com pop-up, som e vibração no celular
- **Lista de tarefas** com sugestões prontas, criação livre e marcação de concluídas
- **Três paletas de cores**: Clássica, Doce e Aurora
- **Janela flutuante** que fica visível enquanto você usa outros sites ou programas
- **Gráficos** que mostram a duração do ciclo e a proporção entre foco e descanso
- **Preferências salvas** no navegador (tempos, paleta e tarefas)

## Como usar

1. Baixe o arquivo `index.html`
2. Abra o arquivo em qualquer navegador moderno
3. Escolha uma tarefa, clique em **Iniciar** e foque até o aviso

Não é preciso instalar dependências, rodar servidor ou fazer build.

## Tecnologias

- **HTML** para a estrutura da página
- **CSS** com variáveis para cores, temas e layout responsivo
- **JavaScript** puro, sem frameworks
- **Web Audio API** para o som de aviso
- **Document Picture-in-Picture API** para a janela flutuante
- **localStorage** para salvar as preferências

## Compatibilidade

O timer funciona em todos os navegadores modernos, no computador e no celular. A janela flutuante interativa funciona no **Chrome** e no **Edge** para computador. Em outros navegadores, ela é exibida como vídeo (sem botões) ou pode não estar disponível.

## Créditos

Page by Maxinani.

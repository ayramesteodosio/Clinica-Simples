# Clínica Médica - Projeto de Site

Este repositório contém o projeto de um site simples para uma clínica médica, desenvolvido com HTML e CSS. O objetivo do projeto é praticar conceitos fundamentais de desenvolvimento web, incluindo a criação de páginas estruturadas, uso de formulários, tabelas e aplicação de estilos com CSS.

---

## 📄 Estrutura do Projeto

O projeto é composto por quatro páginas principais:

1. **Página Principal (`index.html`)**:
   - Apresenta uma breve descrição da clínica.
   - Contém o cabeçalho com uma imagem de destaque.
   
2. **Sobre a Clínica (`sobre.html`)**:
   - Contém informações detalhadas sobre a clínica, sua história e especialidades.

3. **Horário de Atendimento (`horario.html`)**:
   - Exibe os horários de funcionamento por serviço em formato de tabela.
   - Inclui imagens e textos relacionados aos serviços.

4. **Contato (`contato.html`)**:
   - Contém informações de contato, como telefone e endereço.
   - Possui um formulário de contato com os campos:
     - Nome
     - E-mail
     - Assunto
     - Mensagem
   - Integração com o Google Maps para localização da clínica.

---

## 📁 Estrutura de Arquivos

├── index.html           # Página Principal
├── rotas                # Pasta Para Rota das Outras Páginas
    ├── sobre.html       # Sobre a Clínica
    ├── horario.html     # Horário de Atendimento
    ├── contato.html     # Página de Contato
├── style.css         # Estilos CSS para o site
├── img/             # Pasta para imagens utilizadas no site
└── README.md        # Documentação do projeto

## 🎨 Estilo e Layout
O layout do site foi desenvolvido com base em um arquivo CSS único (style.css), contendo:

- Header: Ocupa toda a largura no topo da página.
- Menu: Fixo no lado esquerdo, com links para navegação entre as páginas.
- Conteúdo: Espaço principal ao lado do menu para cada página.
- Footer: Rodapé com informações de contato.

### Principais Estilos Aplicados:

- Menu Fixo: Configurado com position: fixed e largura de 200px.
- Header Responsivo: Imagem que ocupa toda a largura disponível.
- Desabilitação de Ajuste do <textarea>: Implementado com resize: none.
- Tabela: Utilizada para exibir horários e serviços.

## 🌐 Como Visualizar o Projeto
Para visualizar o projeto localmente:

Faça o clone deste repositório:
````
git clone https://github.com/usuario/projeto-clinica.git
````
Navegue até o diretório do projeto:
````
cd projeto-clinica
````    
Abra o arquivo index.html no navegador.

## 🚀 Funcionalidades
- Navegação intuitiva com links em todas as páginas.
- Formulário funcional para entrada de dados.
- Estilização consistente com CSS.
- Layout responsivo que ocupa toda a largura da tela.
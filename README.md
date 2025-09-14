# 🌲 Minha Árvore de Natal Interativa

Um projeto web interativo que cria uma árvore de natal 3D usando Three.js, onde os usuários podem clicar para adicionar enfeites coloridos que giram ao redor da árvore.

## ✨ Funcionalidades

- **Renderização 3D**: Árvore de natal criada com Three.js
- **Interatividade**: Clique para adicionar bolas coloridas à árvore
- **Animações**: 
  - Bolas decorativas que giram ao redor da árvore
  - Efeito de neve caindo continuamente
  - Animação de crescimento das bolas ao serem adicionadas
- **Efeitos Sonoros**: Sons de clique e música de fundo (implementação necessária)
- **Design Responsivo**: Adapta-se a diferentes tamanhos de tela

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6 modules)
- [Three.js](https://threejs.org/) (v0.164.0) - Biblioteca 3D WebGL
- WebGL para renderização gráfica

## 📦 Instalação e Uso

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/minha-arvore-natal.git
```

2. Navegue até o diretório do projeto:
```bash
cd minha-arvore-natal
```

3. Adicione os arquivos de áudio na pasta do projeto:
   - `click-sound.mp3` - Som ao clicar na árvore
   - `background-music.mp3` - Música de fundo natalina

4. Abra o arquivo `index.html` em seu navegador ou sirva através de um servidor local.

## 🎮 Como Usar

- Clique em qualquer lugar na cena para adicionar uma bola colorida à árvore
- As bolas serão posicionadas e começarão a girar ao redor da árvore
- Assista a neve cair continuamente no cenário

## 🎨 Estrutura do Projeto

```
minha-arvore-natal/
├── index.html          # Estrutura principal HTML
├── style.css           # Estilos da aplicação
├── main.js             # Lógica principal com Three.js
├── click-sound.mp3     # Efeito sonoro de clique (a adicionar)
└── background-music.mp3 # Música de fundo (a adicionar)
```

## 🔧 Personalização

É possível personalizar a árvore modificando os parâmetros no arquivo `main.js`:

```javascript
const params = {
    stripesNumber: 15,    # Número de "faixas" que compõem a árvore
    stripeWidth: .03,     # Largura de cada faixa
};
```

## 🌐 Compatibilidade

- Navegadores modernos com suporte a WebGL
- Dispositivos móveis e desktop

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

⭐️ Se você gostou deste projeto, não se esqueça de dar uma estrela no repositório!

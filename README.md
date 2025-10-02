# 🌍 WebWorldDiscovery

> **Desafio Capítulo 6 - Curso HTML NetAcad (Cisco)**

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)

**Uma aplicação web interativa para descobrir informações geográficas dos continentes**

[🌐 Ver Demo](#-funcionalidades) • [📚 Documentação](#-sobre-o-projeto) • [🚀 Como Usar](#-como-usar)

</div>

---

## 📋 Sobre o Projeto

O **WebWorldDiscovery** é uma aplicação web educativa desenvolvida como parte do **Capítulo 6** do curso de HTML da **NetAcad (Cisco)**. O projeto demonstra conceitos avançados de HTML5, CSS3 e JavaScript, incluindo:

- 🗺️ **Image Maps** com áreas clicáveis
- 📍 **Geolocation API** para detectar localização
- 🎨 **CSS moderno** com gradientes e animações
- 📱 **Design responsivo** para todos os dispositivos
- ⚡ **JavaScript interativo** com modais e efeitos

## 🎯 Funcionalidades

### 🌟 Principais Recursos

| Funcionalidade | Descrição | Status |
|---|---|---|
| 🗺️ **Mapa Interativo** | Clique em qualquer continente para ver informações | ✅ Ativo |
| 📍 **Geolocalização** | Detecta automaticamente seu continente | ✅ Ativo |
| 🏔️ **Informações Geográficas** | Rios, montanhas e pontos turísticos | ✅ Ativo |
| 🎨 **Modal Elegante** | Interface moderna para exibir dados | ✅ Ativo |
| 📱 **Responsividade** | Funciona em desktop, tablet e mobile | ✅ Ativo |
| 🌙 **Animações Suaves** | Transições e efeitos visuais | ✅ Ativo |

### 🌍 Continentes Disponíveis

<div align="center">

| 🌎 América do Norte | 🌎 América do Sul | 🌍 Europa |
|---|---|---|
| **Rio:** Mississippi | **Rio:** Amazonas | **Rio:** Danúbio |
| **Montanha:** Denali | **Montanha:** Aconcágua | **Montanha:** Monte Branco |
| **Pontos:** Grand Canyon, Estátua da Liberdade | **Pontos:** Machu Picchu, Ilhas Galápagos | **Pontos:** Torre Eiffel, Coliseu |

| 🌍 África | 🌏 Ásia | 🌏 Oceania |
|---|---|---|
| **Rio:** Nilo | **Rio:** Yangtzé | **Rio:** Murray |
| **Montanha:** Kilimanjaro | **Montanha:** Everest | **Montanha:** Kosciuszko |
| **Pontos:** Esfinge, Montanha da Mesa | **Pontos:** Muralha da China, Petra | **Pontos:** Ópera de Sydney, Uluru |

</div>

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica e image maps
- **CSS3** - Estilização moderna com Flexbox e animações
- **JavaScript ES6+** - Interatividade e APIs do navegador
- **FontAwesome** - Ícones vetoriais

### APIs & Recursos
- **Geolocation API** - Detecção de localização do usuário
- **DOM Manipulation** - Interação dinâmica com elementos
- **Event Handling** - Gerenciamento de eventos de clique e teclado

## 🚀 Como Usar

### 1️⃣ **Método da Geolocalização**
1. Clique no botão **"🎯 Descobrir Minha Localização"**
2. Permita o acesso à sua localização quando solicitado
3. Aguarde o carregamento (spinner animado)
4. Veja as informações do seu continente no modal

### 2️⃣ **Método do Mapa Interativo**
1. Observe o mapa-múndi na página
2. Clique diretamente no continente desejado
3. O modal se abrirá instantaneamente com as informações

### 3️⃣ **Navegação do Modal**
- **Fechar:** Clique no ❌ ou pressione `ESC`
- **Informações:** Veja rios 💧, montanhas 🏔️ e pontos turísticos 🏛️

## 📁 Estrutura do Projeto

```
WebWorldDiscovery/
├── 📄 index.htm          # Página principal com HTML, CSS e JavaScript
├── 📖 README.md          # Documentação do projeto
└── 🔗 Links externos     # FontAwesome e imagens da NetAcad
```

## 🎓 Conceitos Educacionais (NetAcad)

Este projeto demonstra os seguintes conceitos do **Capítulo 6**:

### 🗺️ **Image Maps**
```html
<img src="mapa.jpg" usemap="#image-map">
<map name="image-map">
    <area coords="x1,y1,x2,y2" shape="rect" id="continente">
</map>
```

### 📍 **Geolocation API**
```javascript
navigator.geolocation.getCurrentPosition(
    position => {
        const lat = position.coords.latitude;
        const lng = position.coords.longitude;
    }
);
```

### 🎨 **CSS Moderno**
- Gradientes lineares e radiais
- Transformações e transições
- Flexbox para layout responsivo
- Animações keyframes

## 🎨 Preview Visual

<div align="center">

### 🖥️ **Desktop**
*Interface principal com mapa interativo e botão de geolocalização*

### 📱 **Mobile**
*Layout responsivo adaptado para dispositivos móveis*

### 🎭 **Modal**
*Exibição elegante das informações geográficas*

</div>

## 🌟 Melhorias Implementadas

### 🎨 **Design**
- ✨ Interface moderna com gradientes
- 🎭 Modal substituindo alerts simples
- 🎪 Animações suaves e transições
- 📱 Design totalmente responsivo
- 🎨 Paleta de cores harmoniosa

### ⚡ **Funcionalidade**
- 🔄 Loading indicator durante geolocalização
- 🎯 Melhor tratamento de erros
- ⌨️ Suporte a teclas (ESC para fechar)
- 🖱️ Efeitos hover interativos
- 📊 Feedback visual aprimorado

## 👨‍💻 Autor

**MARISTELAOLIVEIRA**
- 🎓 Estudante do curso NetAcad (Cisco)
- 📧 Capítulo 6 - HTML Avançado
- 🌍 Projeto: WebWorldDiscovery

---

<div align="center">

### 📚 **Feito com ❤️ para o curso NetAcad** 

**🌍 Descubra o mundo, um clique de cada vez! 🌍**

---

*Este projeto é parte dos exercícios educacionais do curso de HTML da Cisco NetAcad*

</div>Web World Discovery
Desafio capítulo 6 NetAcad

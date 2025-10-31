# Sistema de Reservas de Hotel 🏨

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Um sistema web completo para gerenciamento de reservas de hotel desenvolvido com **HTML**, **CSS** e **JavaScript**.

## 📋 Índice

- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades-✨)
- [Tecnologias](#tecnologias-🛠️)
- [Estrutura do Projeto](#estrutura-do-projeto-📁)
- [Instalação e Uso](#instalação-e-uso-🚀)
- [Capturas de Tela](#capturas-de-tela-📸)
- [API e Dados](#api-e-dados-💾)
- [Contribuição](#contribuição-🤝)
- [Licença](#licença-📄)

## Visão Geral

O **Sistema de Reservas de Hotel** é uma aplicação web responsiva que permite aos usuários pesquisar disponibilidade, visualizar quartos e fazer reservas de forma intuitiva. Desenvolvido com tecnologias front-end modernas, oferece uma experiência de usuário fluida e agradável.

## Funcionalidades ✨

### 🎯 Principais
- **Busca Inteligente**: Pesquisa por datas, número de hóspedes e tipo de quarto
- **Visualização de Quartos**: Galeria com fotos e detalhes dos quartos
- **Processo de Reserva**: Sistema em etapas para reservas simplificadas
- **Validação em Tempo Real**: Verificação de dados durante o preenchimento
- **Design Responsivo**: Adaptável a todos os dispositivos

### 🔧 Administrativas
- Gestão de disponibilidade
- Controle de reservas
- Simulação de confirmações
- Persistência de dados local

## Tecnologias 🛠️

### Frontend
- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Flexbox, Grid, animações e variáveis CSS
- **JavaScript ES6+**: Modules, classes e manipulação do DOM

### Recursos
- **LocalStorage**: Persistência de dados no navegador
- **Responsive Design**: Mobile-first approach
- **CSS Variables**: Sistema consistente de cores e espaçamento

## Estrutura do Projeto 📁

```
hotel-reservation-system/
├── index.html                 # Página principal
├── css/
│   ├── style.css             # Estilos principais
│   ├── responsive.css        # Media queries
│   └── variables.css         # Variáveis CSS
├── js/
│   ├── main.js               # Inicialização da aplicação
│   ├── reservation.js        # Lógica de reservas
│   ├── search.js             # Sistema de busca
│   ├── ui.js                 # Manipulação da interface
│   └── utils.js              # Funções utilitárias
├── images/                   # Assets visuais
│   ├── rooms/
│   ├── icons/
│   └── background.jpg
└── README.md                 # Documentação
```

## Instalação e Uso 🚀

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional, para desenvolvimento)

### Instalação Rápida

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/hotel-reservation-system.git
   ```

2. **Acesse o diretório**
   ```bash
   cd hotel-reservation-system
   ```

3. **Execute o projeto**
   - Abra o arquivo `index.html` no navegador
   - Ou use um servidor local:
   ```bash
   # Com Python
   python -m http.server 8000
   
   # Com Node.js
   npx http-server
   ```

### Desenvolvimento

Para contribuir com o projeto:

1. Faça o fork do repositório
2. Crie uma branch para sua feature
   ```bash
   git checkout -b feature/nova-funcionalidade
   ```
3. Commit suas mudanças
   ```bash
   git commit -m 'Adiciona nova funcionalidade'
   ```
4. Push para a branch
   ```bash
   git push origin feature/nova-funcionalidade
   ```

## Capturas de Tela 📸

### Página Inicial
![Página Inicial](images/screenshots/homepage.png)

### Busca de Quartos
![Busca](images/screenshots/search.png)

### Detalhes do Quarto
![Detalhes](images/screenshots/room-details.png)

## API e Dados 💾

### Estrutura de Dados

```javascript
// Exemplo de objeto Quarto
{
  id: 1,
  name: "Suíte Luxo",
  type: "luxury",
  price: 299,
  capacity: 3,
  available: 2,
  amenities: ["Wi-Fi", "TV LED", "Ar Condicionado", "Varanda"],
  images: ["suite-luxo-1.jpg", "suite-luxo-2.jpg"],
  description: "Suíte espaçosa com vista para o mar"
}
```

### LocalStorage

Os dados são persistidos usando localStorage:

```javascript
// Chaves utilizadas
- 'hotelRooms'       // Catálogo de quartos
- 'reservations'     // Reservas ativas
- 'searchHistory'    // Histórico de buscas
```

## Funcionalidades Detalhadas

### 🔍 Sistema de Busca
- Filtros por data, hóspedes e tipo de quarto
- Validação de datas (não permite datas passadas)
- Busca em tempo real

### 📅 Gestão de Reservas
- Processo em 3 etapas
- Confirmação instantânea
- Cancelamento de reservas
- Histórico de reservas

### 📱 Design Responsivo
- **Mobile**: Layout otimizado para touch
- **Tablet**: Adaptação do grid de quartos
- **Desktop**: Experiência completa com sidebar

## Contribuição 🤝

Contribuições são sempre bem-vindas! Por favor, leia as diretrizes de contribuição antes de submeter alterações.

### Reportando Bugs
1. Verifique se o bug já não foi reportado
2. Use o template de bug report
3. Inclua steps para reproduzir

### Sugerindo Melhorias
1. Abra uma issue com a label "enhancement"
2. Descreva claramente a funcionalidade
3. Explique o valor agregado

## Roadmap 🗺️

### Versão 1.1
- [ ] Integração com API de pagamento
- [ ] Sistema de avaliações
- [ ] Modo escuro

### Versão 1.2
- [ ] Chatbot de atendimento
- [ ] App PWA
- [ ] Multi-idioma

### Futuro
- [ ] App nativo
- [ ] Integração com sistemas de terceiros
- [ ] Analytics avançado

## Licença 📄

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para detalhes.

## Contato 📞

- **Desenvolvedor**: [Seu Nome](https://github.com/seu-usuario)
- **Email**: seu.email@example.com
- **LinkedIn**: [Seu Perfil](https://linkedin.com/in/seu-perfil)

## Agradecimentos 🙏

- Ícones por [FontAwesome](https://fontawesome.com)
- Imagens por [Unsplash](https://unsplash.com)
- Inspiração de design por [Dribbble](https://dribbble.com)

---

**⭐️ Se este projeto te ajudou, considere dar uma estrela no repositório!**

---

<div align="center">
  
Feito com ❤️ e ☕ por [Seu Nome]

[⬆ Voltar ao topo](#sistema-de-reservas-de-hotel-)

</div>
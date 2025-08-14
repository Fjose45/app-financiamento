# Sistema de Financiamentos Crefisa - PWA

Um Progressive Web App (PWA) completo para gestão de financiamentos, consultores e acessos, desenvolvido especificamente para dispositivos móveis.

## 🚀 Características

### PWA Features
- ✅ **Instalação nativa** - Pode ser instalado como app no smartphone
- ✅ **Funcionamento offline** - Cache inteligente para uso sem internet
- ✅ **Responsivo total** - Layout otimizado para mobile e tablet
- ✅ **Compatibilidade multiplataforma** - Android (Chrome) e iOS (Safari)
- ✅ **Notificações push** - Alertas em tempo real
- ✅ **Atalhos rápidos** - Acesso direto às principais funcionalidades
- ✅ **Sincronização automática** - Dados sempre atualizados

### Funcionalidades do Sistema
- 📊 **Gestão de Financiamentos** - Cadastro, edição e relatórios
- 👥 **Relatório de Consultores** - Análise de performance por consultor
- 🔑 **Controle de Acessos** - Gestão de novos usuários
- 📱 **Interface mobile-first** - Otimizada para toque
- 📄 **Exportação PDF** - Relatórios profissionais
- 💾 **Armazenamento local** - Dados salvos no dispositivo

## 📱 Como Instalar

### Android (Chrome)
1. Abra o Chrome e acesse o sistema
2. Aguarde o prompt de instalação aparecer (ou clique no ícone de instalação na barra de endereços)
3. Toque em "Instalar" ou "Adicionar à tela inicial"
4. O app será instalado e aparecerá na tela inicial

### iOS (Safari)
1. Abra o Safari e acesse o sistema
2. Toque no botão de compartilhar (ícone quadrado com seta)
3. Selecione "Adicionar à Tela Inicial"
4. Toque em "Adicionar"
5. O app aparecerá na tela inicial

### Desktop
1. Abra o Chrome/Edge e acesse o sistema
2. Clique no ícone de instalação na barra de endereços
3. Clique em "Instalar"
4. O app será instalado como aplicativo desktop

## 🎯 Atalhos Rápidos

Após a instalação, você pode usar atalhos para acessar diretamente:

- **Novo Financiamento** - Cadastrar financiamento rapidamente
- **Relatório Consultores** - Visualizar performance dos consultores
- **Novos Acessos** - Gerenciar acessos de usuários

## 🔧 Configuração Técnica

### Arquivos PWA
- `manifest.json` - Configuração do app
- `sw.js` - Service Worker para funcionalidade offline
- `moeda_*.png` - Ícones em diferentes tamanhos

### Requisitos do Servidor
- Servidor HTTPS (obrigatório para PWA)
- Headers CORS configurados
- MIME types corretos para manifest.json

### Estrutura de Arquivos
```
/
├── index.html          # Página principal
├── manifest.json       # Configuração PWA
├── sw.js              # Service Worker
├── moeda_192.png      # Ícone 192x192
├── moeda_256.png      # Ícone 256x256
├── moeda_384.png      # Ícone 384x384
├── moeda_512.png      # Ícone 512x512
└── README.md          # Este arquivo
```

## 📊 Funcionalidades Detalhadas

### 1. Financiamentos
- Cadastro com validação de CPF
- Filtros por período
- Edição e exclusão
- Exportação para PDF
- Cálculo automático de totais

### 2. Consultores
- Relatório automático por consultor
- Quantidade de vendas
- Valor total por consultor
- Exportação para PDF

### 3. Acessos
- Cadastro de novos usuários
- Validação de email e telefone
- Gestão completa de acessos
- Exportação para PDF

## 🎨 Design Responsivo

### Breakpoints
- **Mobile**: < 768px - Layout em coluna única
- **Tablet**: 768px - 1024px - Layout adaptativo
- **Desktop**: > 1024px - Layout completo

### Características Mobile
- Touch-friendly buttons
- Swipe gestures
- Safe area insets (iPhone)
- PWA standalone mode

## 🔒 Segurança e Privacidade

- Dados armazenados localmente (localStorage)
- Sem envio de dados para servidores externos
- Validação client-side robusta
- Compatível com políticas de privacidade

## 🚀 Performance

- Cache inteligente de recursos
- Lazy loading de componentes
- Otimização para conexões lentas
- Compressão de imagens

## 📱 Compatibilidade

### Navegadores Suportados
- ✅ Chrome 67+
- ✅ Safari 11.1+
- ✅ Firefox 67+
- ✅ Edge 79+

### Sistemas Operacionais
- ✅ Android 5.0+
- ✅ iOS 11.3+
- ✅ Windows 10+
- ✅ macOS 10.13+

## 🛠️ Desenvolvimento

### Tecnologias Utilizadas
- HTML5
- CSS3 (Tailwind CSS)
- JavaScript ES6+
- PWA APIs
- Service Workers

### Bibliotecas Externas
- Tailwind CSS (CDN)
- jsPDF (PDF generation)
- Font Awesome (Ícones)

## 📞 Suporte

Para suporte técnico ou dúvidas:
- **Desenvolvedor**: Fabíola Albuquerque Pereira
- **Email**: [seu-email@exemplo.com]
- **Telefone**: [seu-telefone]

## 📄 Licença

Este projeto é de uso interno da Fabiola. Todos os direitos reservados.

---

**Versão**: 1.0.0  
**Última atualização**: Agosto 2025  
**Desenvolvido por**: Francisco Jose da silva pereira

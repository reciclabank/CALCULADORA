# Como usar Cursor no iPhone 12

## ⚠️ Informação Importante
O **Cursor** é um editor de código desktop que **não possui versão nativa para iPhone**. No entanto, existem várias alternativas para programar e editar código no seu iPhone 12.

## 🔄 Alternativas para Programar no iPhone 12

### 1. **Acesso Remoto ao Cursor Desktop**

#### Via SSH + Terminal
```bash
# No seu computador com Cursor instalado:
# 1. Instale um servidor SSH se não tiver
# 2. Configure acesso remoto

# No iPhone, use apps como:
# - Termius (SSH client)
# - Blink Shell
# - Working Copy (Git client com terminal)
```

#### Via VNC/Remote Desktop
- **Jump Desktop** - Acesso remoto ao desktop
- **TeamViewer** - Controle remoto
- **Chrome Remote Desktop** - Via navegador

### 2. **Editores de Código Nativos para iPhone**

#### 📱 Apps Recomendados:
1. **Working Copy** (Git + Editor)
   - Suporte completo ao Git
   - Syntax highlighting
   - Integração com GitHub/GitLab
   - Editor poderoso

2. **Buffer Editor**
   - Editor de código completo
   - Suporte a múltiplas linguagens
   - Themes personalizáveis

3. **Koder**
   - Syntax highlighting
   - FTP/SFTP support
   - Múltiplas abas

4. **Textastic**
   - Editor avançado
   - Suporte a 80+ linguagens
   - Preview HTML/Markdown

### 3. **Desenvolvimento Web no Navegador**

#### Plataformas Online:
1. **GitHub Codespaces**
   - VS Code no navegador
   - Ambiente completo de desenvolvimento
   - Acesso via Safari no iPhone

2. **Repl.it**
   - IDE online
   - Múltiplas linguagens
   - Colaboração em tempo real

3. **CodeSandbox**
   - Desenvolvimento web
   - React, Vue, Angular
   - Preview em tempo real

4. **Gitpod**
   - Workspace baseado em VS Code
   - Integração com Git
   - Containers pré-configurados

### 4. **Configuração Híbrida (Recomendado)**

#### Setup Ideal:
1. **Computador Principal**: Cursor instalado
2. **Sincronização**: Git + GitHub/GitLab
3. **iPhone**: Working Copy + editor web
4. **Workflow**:
   ```
   iPhone (edição rápida) → Git push → 
   Computador (desenvolvimento principal) → 
   Git pull → Cursor
   ```

## 📋 Guia Passo a Passo

### Para Acesso Remoto:
1. **Instale Termius** na App Store
2. **Configure SSH** no seu computador
3. **Conecte-se remotamente** e use Cursor via terminal
4. **Use tmux/screen** para sessões persistentes

### Para Desenvolvimento Local:
1. **Baixe Working Copy** (melhor opção gratuita)
2. **Clone seu repositório**
3. **Configure sincronização automática**
4. **Use editor integrado** para mudanças rápidas

### Para Desenvolvimento Web:
1. **Acesse GitHub.com** no Safari
2. **Pressione "."** em qualquer repositório
3. **Use GitHub Codespaces** (VS Code no navegador)
4. **Desenvolva diretamente** no iPhone

## 💡 Dicas Importantes

### Produtividade:
- Use **teclado Bluetooth** para digitação mais confortável
- Configure **atalhos de teclado** nos apps
- Use **Split View** para múltiplas janelas
- Aproveite **Siri Shortcuts** para automações

### Limitações do iPhone:
- Tela pequena para código complexo
- Sem suporte a extensões do Cursor
- Processamento limitado
- Bateria se esgota mais rápido

### Recomendações:
1. **Use iPhone para**: edições rápidas, revisões, commits
2. **Use computador para**: desenvolvimento principal, debugging
3. **Mantenha sincronização** constante via Git
4. **Configure notificações** para builds/deploys

## 🔧 Configuração Específica para este Projeto

Baseado no seu projeto CALCULADORA:

```bash
# 1. Clone no Working Copy
git clone https://github.com/reciclabank/CALCULADORA

# 2. Configure branch atual
git checkout cursor/enable-cursor-on-iphone-12-72a1

# 3. Faça edições no iPhone
# 4. Commit e push
git add .
git commit -m "Edições feitas no iPhone 12"
git push origin cursor/enable-cursor-on-iphone-12-72a1
```

## 📞 Suporte

Se precisar de ajuda específica:
1. Verifique a documentação do app escolhido
2. Use fóruns da comunidade iOS
3. Considere usar iPad para melhor experiência

---

**Resumo**: Embora não exista Cursor nativo para iPhone, você pode usar acesso remoto, editores nativos ou IDEs web para programar efetivamente no seu iPhone 12.
# 🌟 Solaris PRO - Sistema Completo de Gestão para Óticas

O **Solaris PRO** é uma solução moderna e inteligente para o gerenciamento completo de óticas. Desenvolvido com tecnologias web e integração em tempo real com Firebase, o sistema oferece segurança, agilidade e uma interface intuitiva para profissionais da área óptica.

---

## 🔥 Principais Funcionalidades

### 🔐 Autenticação Segura
- Tela de login com Firebase Authentication
- Controle de acesso por níveis de usuário
- Gerenciamento de sessões

### 🔄 Integração com Banco de Dados em Tempo Real
- Conexão com Firebase Firestore
- Sincronização instantânea de dados
- Backup automático na nuvem

### 📦 Módulos Completos
- **Clientes**: Cadastro completo com histórico médico
- **Estoque**: Controle de armações, lentes e acessórios
- **Vendas**: Processo completo com NF-e integrada
- **Agendamentos**: Calendário inteligente com lembretes
- **Laudos**: Editor de receitas médicas, gerador de PDF e modelos personalizáveis
- **Relatórios**: Análise de vendas, desempenho de produtos e rentabilidade por marca

---

## 🧠 Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Firebase (Authentication, Firestore)
- **Bibliotecas**:
  - jsPDF para geração de PDFs
  - Font Awesome para ícones
  - Google Fonts (Apple-like typography)

---

## 🚀 Como Implementar na Sua Ótica

### 🔧 Configuração do Firebase

1. Crie um projeto no [Firebase Console](https://console.firebase.google.com)
2. Ative os serviços:
   - Authentication (Email/Senha)
   - Firestore Database
3. Copie as credenciais do Firebase e substitua no código:
   ```javascript
   const firebaseConfig = {
     apiKey: "SUA_API_KEY",
     authDomain: "SEU_PROJETO.firebaseapp.com",
     projectId: "SEU_PROJETO",
     storageBucket: "SEU_PROJETO.appspot.com",
     messagingSenderId: "SEU_SENDER_ID",
     appId: "SEU_APP_ID"
   };
   firebase.initializeApp(firebaseConfig);
Crie o usuário administrador manualmente:

E-mail: admin@admin.com

Senha: admin123

⚠️ Após o primeiro login, altere a senha padrão em Configurações > Minha Conta.

👨‍💼 Níveis de Acesso
Perfil	Permissões
Administrador	Acesso total a todos os módulos
Gerente	Vendas, estoque, clientes
Optometrista	Laudos, agendamentos
Vendedor	Apenas vendas e clientes
🛠️ Solução de Problemas Comuns
E-mail não encontrado: Verifique se digitou corretamente ou contate o administrador.

Senha incorreta: Clique em "Esqueci minha senha" ou tente novamente.

Erro de conexão: Verifique sua internet ou as chaves do Firebase.

📈 Benefícios para Sua Ótica
Controle total do fluxo de clientes e estoque

Redução de erros com processos automatizados

Aumento de produtividade com interface intuitiva

Tomada de decisão baseada em dados reais

Conformidade com exigências do CRM para receituários

🤝 Como Contribuir
Contribuições são bem-vindas! Para colaborar:

Faça um Fork do projeto

Crie uma Branch:

bash
git checkout -b feature/minha-feature
Faça o Commit:

bash
git commit -m "Adiciona minha-feature"
Envie para o GitHub:

bash
git push origin feature/minha-feature
Abra um Pull Request

📄 Licença
Este projeto está licenciado sob os termos da MIT License.

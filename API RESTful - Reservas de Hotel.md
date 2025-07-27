
---

## **Backlog da API RESTful - Reservas de Hotel**

### **1. Usuários & Autenticação** ✅ **[Essencial]**

- [ ]  Cadastro de usuário (nome, e-mail, senha)
- [ ]  Login e autenticação (JWT)
- [ ]  Atualização de perfil (nome, senha)
- [ ]  Exclusão de conta

---

### **2. Gerenciamento de Quartos** ✅ **[Essencial]**

- [ ]  Criar um quarto (admin)
- [ ]  Listar todos os quartos
- [ ]  Buscar quarto por ID
- [ ]  Atualizar informações do quarto (admin)
- [ ]  Excluir um quarto (admin)

📌 **Campos do quarto:** número, tipo (simples, luxo, suíte), preço por noite, status (disponível ou ocupado).

---

### **3. Reservas** ✅ **[Essencial]**

- [ ]  Criar uma reserva (usuário seleciona um quarto e período)
- [ ]  Listar reservas do usuário
- [ ]  Cancelar reserva (somente se ainda não começou e dentro do prazo de cancelamento)
- [ ]  Listar todas as reservas (admin)
- [ ]  Verificar se o usuário tem uma reserva ativa (antes do check-in)
- [ ]  Realizar o check-in (admin ou sistema automático)
- [ ]  Realizar o check-out (admin ou sistema automático)

📌 **Regras:**  
✔️ Um quarto só pode ser reservado se estiver disponível.  
✔️ O usuário deve fornecer datas de check-in e check-out.  
✔️ O check-in pode ser realizado apenas se a reserva estiver confirmada e a data de check-in for atingida.  
✔️ O cancelamento da reserva deve ocorrer até 24 horas antes do **check-in**.

---

### **4. Pagamentos (Opcional, se quiser expandir)**

- [ ]  Criar pagamento vinculado a uma reserva
- [ ]  Consultar status do pagamento
- [ ]  Cancelamento de pagamento

---

### **5. Relatórios (Opcional, para aprendizado extra)**

- [ ]  Relatório de ocupação dos quartos
- [ ]  Total de reservas por mês

Esse backlog agora inclui o processo de **check-in** e **check-out**, além de regras específicas para cancelamento de reserva. Se precisar de mais alguma coisa, é só avisar! 🚀
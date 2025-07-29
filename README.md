echo "# Testes-Automatizados-com-Pytest." >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Diego-felipe1989/Testes-Automatizados-com-Pytest..git
git push -u origin main

---

## ✅ Exemplos de Casos de Teste

- Teste de login com credenciais válidas e inválidas  
- Validação de campos obrigatórios  
- Testes com dados inválidos (e-mail incorreto, campos vazios)  
- Garantia de que o botão “Enviar” só funciona com todos os campos preenchidos  
- Verificação de mensagens de erro

---

## 📦 Como Executar Localmente

### 1. Clonar o repositório
```bash
git clone https://github.com/Diego-felipe1989/testes-automatizados-pytest.git
cd testes-automatizados-pytest
python -m venv venv
# Linux/Mac
source venv/bin/activate
# Windows
venv\Scripts\activate

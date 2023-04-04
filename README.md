# red-bank

Criar um usuario:

- Pagina inicial para criar a conta:
  - Nome completo:
  - Data de nascimento:
  - CPF:
  - E-mail:
  - Senha:
  - Confirmação de senha:
  
- Página 2 (Confirmação de email):
  - Código que foi enviado no e-mail
  
- Pagina 3 (Residencia):
  - CEP:
  - Rua:
  - Complemento:
  - Comprovante de residencia:
  
- Página 4 (Comprovação de indentidade):
  - Foto do documento:
  - Foto do usuario:
  
  
 - Schema Final:
    - nome: string;
    - data_nascimento: string;
    - cpf: string;
    - email: string;
    - senha: string;
    - endereco: string;
    - foto: number;
    - ip: string;
    - saldo: number

- Validações no processo:
    - Data de nascimento: Validar se é maior ou igual que 18 anos; 
    - CPF: Buscar pelo cpf em alguma api, se estiver ok, comparar com o nome e data de nascimento;
    - Senha: deve conter mais que 8 digitos e incluir Numeros e letras;
    - COD: validar

# Desafio Complementar Ignite - Node.js (MiddleWares).

### Nesse desafio, foi realizado a criação de Middlewares para uma aplicação em Node.js

<span style="font-family: 'Poppins', sans-serif;font-size:11pt">
Funcionalidade dos Middlewares criados <br />

- checksExistsUserAccount - Responsável por receber o username do usuário pelo header e validar se existe ou não um usuário com o username passado

- checksCreateTodosUserAvailability - Deve receber o usuário já dentro do request e chamar a função next apenas se esse usuário ainda estiver no plano grátis e ainda não possuir 10 todos cadastrados ou se ele já estiver com o plano Pro ativado.

- checksTodoExists - Deve receber o **username** de dentro do header e o **id** de um _todo_ de dentro de `request.params`. Você deve validar o usuário, validar que o `id` seja um uuid e também validar que esse `id` pertence a um _todo_ do usuário informado. Com todas as validações passando, o _todo_ encontrado deve ser passado para o `request` assim como o usuário encontrado também e a função next deve ser chamada.

- findUserById - Funcionamento semelhante ao middleware checksExistsUserAccount mas a busca pelo usuário deve ser feita através do id de um usuário passado por parâmetro na rota. Caso o usuário tenha sido encontrado, o mesmo deve ser repassado para dentro do request.user e a função next deve ser chamada.
  </span>

### Todos os tests passaram: Para conferir => Clone a aplicação e digite **`yarn test`** no terminal

<div> 
  
  <a href = "mailto:ericpandrade085@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=red" target="_blank"></a>
  <a href="https://www.linkedin.com/in/eric-andrade-872a01210/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href="https://api.whatsapp.com/send?phone=+5585989828188&text=Olá! Gostaria de entrar em contato." target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a>

</div>

<span style="font-family: 'Poppins', sans-serif;font-size:9pt; font-style:italic">
Projeto feito por Eric Pereira Andrade.
</span>

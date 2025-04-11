### Nome
Diego Furigo do Nascimento
### RM
rm558755

---

## Descrição das funcionalidades
**Aplicação de marcação de consultas médicas onde possui as seguintes funcionalidades:**
- Cadastro de pacientes e médicos, com controle de dados básicos de cada entidade.
> Paciente (agenda e visualiza histórico)

> Médico (confirma ou cancela consultas)

> Administrador (gerencia usuários e consultas)

- Agendamento de consultas, onde é possível vincular médico, paciente, data e horário
- Validações como: horários disponíveis, se o médico já tem consulta naquele horário, e horários dentro do expediente
- Persistência local com AsyncStorage
- Cancelamento de consultas com motivo registrado
- Organização em camadas: entidades, repositórios e serviços, seguindo boas práticas de arquitetura

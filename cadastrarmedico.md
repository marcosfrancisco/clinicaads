```mermaid
flowchart LR
    Funcionario(["Funcionário"])
    subgraph SISTEMA
        UC1((Cadastrar Médico))
        UC2((Agendar Consulta))
    end

    Funcionario --> UC1
    Funcionario --> UC2

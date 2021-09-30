# SGDOC Especialidades

O SGDOC - É um sistema de gestão documental, o seu conceito é muito simples mais prático.
Nele você pode:
    1 - Gerir Funcionários
        a - Adicionar novos funcionarios
        b - Consultar funcionarios
        c - Eliminar funcionarios
        d - Alterar dados de funcionarios
    2 - Gerir Empresas
        a - Criar novas Empresas
        b - Consultar, Alterar Dados e Eliminar empresas existentes
    3 - Gerir Departamentos
        a - Criar Departamentos
        b - Consultar, Alterar Dados e Eliminar Departamentos existentes
    4 - Gerir Cargos
        a - Criar novos Cargos
        b - Consultar, Alterar Dados e Eliminar Cargos existentes
    3 - Gerir documentos
        a - Criar Documento
        b - Consultar, Alterar Dados e Eliminar Cargos existentes
        c - Verificar o fluxo documental
        d - gerar referencias automáticas
        e - possibilidade de arquivar mais de um ficheiro a um arquivo

O SGDOC Foi feito para trabalhar com multi-Empresas e Departamentos.
O SGDOC tem a integração com a API do Microsoft Graph no Azure de modos a permitir a criação ou o login do funcionario atravez que tenham contas Microsoft.
O SGDOC Tem 3 niveis de acesso:
    1 - Administrador | Que tem acesso a todas as funcionalidades do sistema
    2 - Burocrático | Gere a maioria das funcionalidades principais do sistema
    3 - Comun Nivel | de acesso para leitura apenas
O SGDOC tem integração com o PHP mailer para gerir noificações por e-mail, quando um documento/arquivo é especificado para alguém
O SGDOC possui um sistema de fluxo documental que permite verificar por quais, processos, funcionarios e departamentos, o Documento/Arquivo passou ate ser aprovado.


Futuramente pretende-se fazer a integração com a API do Google, Facebook e outras para login
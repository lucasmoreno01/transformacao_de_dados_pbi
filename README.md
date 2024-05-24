No projeto eu utilizei um servidor local do MYSQL, por conta de probelmas com Azure.

### Processos:
- Limpeza de dados desnecessários;
- Mesclagem de employee e department a fim de associar o colaborador com seu departamento;
- Mesclagem das colunas Fname e Lname separados por "espaço";
- Mesclagem de employee em department para pegar os nomes do gerentes;
- Mesclagem de departmente em emplyee para acossiar os gerentes aos colaboradores;
- Mesclagem de nome do departamento e localização em dept_location;
- Linhas Agrupadas pela coluna Gerente

**Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir:**

Não podemos usar o atribuir pois "Gerente" e "Colaborador" não têm valores em comum. Por isso neste caso utilizamos o mesclar.

# Pipeline ETL para Relatórios de Mediação de Conflitos 🔄

Este é um incrível pipeline ETL (Extração, Transformação e Carregamento) para gerar relatórios de mediação a partir de uma planilha online. ✨

## :gear: Como Usar

1. **Extração (Extract)**:
   - A parte de extração dos dados foi projetada para buscar informações de uma planilha específicas Google Sheets, como banco de dados. 🔍

2. **Transformação (Transform)**:
   - Após a extração, é possível escolher o nome de um cliente da lista e gerar um relatório personalizado com as informções do pós-venda, sobre as informações de mediação. 📊
   - Os dados serão formatados e organizados de acordo com o nome selecionado. 🔄

3. **Carregamento (Load)**:
   - Depois de gerar o relatório, você terá a opção de salvá-lo em um arquivo CSV. 💾
   - O relatório será armazenado no sistema de arquivos local. 📁

4. **Arquivo CSV**:
   - Os relatórios gerados serão salvos em arquivos CSV no diretório "relatorios/". 📄

5. **Agradecimentos**:
   - Este projeto foi desenvolvido como parte da oportunidade de aprendizado fornecida pela DIO em parceria com o Banco Santander. Agradeço imensamente à DIO e ao Santander por essa oportunidade incrível! 🙏

## :computer: Como Executar

Para executar o código, você precisará de Python 3.x e das seguintes bibliotecas instaladas:

```bash
pip install pandas requests
